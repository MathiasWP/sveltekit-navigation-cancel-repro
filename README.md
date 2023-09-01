# navigation.cancel() error

repro of unexpected error thrown in console when canceling navigation:

```ts
client.js?v=2cc7adfe:927 Uncaught (in promise) Error: navigation was cancelled
    at Object.cancel (client.js?v=2cc7adfe:927:16)
    at +page.svelte:5:20
    at client.js?v=2cc7adfe:933:46
    at Array.forEach (<anonymous>)
    at before_navigate (client.js?v=2cc7adfe:933:30)
    at navigate (client.js?v=2cc7adfe:969:15)
    at HTMLHtmlElement.<anonymous> (client.js?v=2cc7adfe:1594:5)
```