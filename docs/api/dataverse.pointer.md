<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@theatre/dataverse](./dataverse.md) &gt; [Pointer](./dataverse.pointer.md)

## Pointer type

<b>Signature:</b>

```typescript
export declare type Pointer<O> = PointerType<O> & (O extends UnindexableTypesForPointer ? UnindexablePointer : unknown extends O ? UnindexablePointer : O extends (infer T)[] ? Pointer<T>[] : O extends {} ? {
    [K in keyof O]-?: Pointer<O[K]>;
} : UnindexablePointer);
```
<b>References:</b> [PointerType](./dataverse.pointertype.md)<!-- -->, [Pointer](./dataverse.pointer.md)

