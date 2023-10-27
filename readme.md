# Single Level Framework

The `Single Level Framework` is an attempt to create an UI framework like Angular, React, Vue, etc.
using JavaScript's built-in Proxy object and a single level array of dom references.

The idea is to use JavaScript's built-in Proxy objects to detect state changes.
When a state change is detected the associated values inside components are reprocessed
and rerendered. At the moment I'm not sure how to properly compute and process conditions
and other mechanics but I see and think about it along with the development.

@see [JavScript Proxy Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy)
