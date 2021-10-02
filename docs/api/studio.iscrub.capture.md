<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@theatre/studio](./studio.md) &gt; [IScrub](./studio.iscrub.md) &gt; [capture](./studio.iscrub.capture.md)

## IScrub.capture() method

Captures operations for the scrub.

Note that running `scrub.capture()` multiple times means all the older calls of `scrub.capture()` will be reset.

<b>Signature:</b>

```typescript
capture(fn: (api: IScrubApi) => void): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fn | (api: IScrubApi) =&gt; void |  |

<b>Returns:</b>

void

## Example

Usage:

```ts
scrub.capture(({set}) => {
  set(obj.props.x, 10) // set the value of obj.props.x to 10
})
```
