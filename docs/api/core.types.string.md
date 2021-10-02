<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@theatre/core](./core.md) &gt; [types](./core.types.md) &gt; [string](./core.types.string.md)

## types.string variable

A string prop type

<b>Signature:</b>

```typescript
string: (defaultValue: string, opts?: PropTypeConfigOpts | undefined) => PropTypeConfig_String
```

## Example

Usage:

```ts
// shorthand:
const obj = sheet.object('key', {message: "Animation loading"})

// with a label:
const obj = sheet.object('key', {
  message: t.string("Animation Loading", {
    label: 'The Message'
  })
})
```
