<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@theatre/studio](./studio.md) &gt; [IScrub](./studio.iscrub.md)

## IScrub interface

<b>Signature:</b>

```typescript
export interface IScrub 
```

## Methods

|  Method | Description |
|  --- | --- |
|  [capture(fn)](./studio.iscrub.capture.md) | Captures operations for the scrub.<!-- -->Note that running <code>scrub.capture()</code> multiple times means all the older calls of <code>scrub.capture()</code> will be reset. |
|  [commit()](./studio.iscrub.commit.md) | Commits the scrub and creates a single undo level. |
|  [discard()](./studio.iscrub.discard.md) | Clearts the ops of the scrub and destroys it. After calling this, you won't be able to call <code>scrub.capture()</code> anymore. |
|  [reset()](./studio.iscrub.reset.md) | Clears all the ops in the scrub, but keeps the scrub open so you can call <code>scrub.capture()</code> again. |

