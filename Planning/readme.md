# Single Level Framework

The `Single Level Framework` is an attempt to create a UI framework like Angular, React, Vue, etc.
using Proxy object and a single level of dom references

The idea is to use JavScript Proxy objects to detect state changes.
When a change is detected the associated values inside components are reprocessed
and rerendered. At the moment I'm not sure how to properly compute and process conditions
or other mechanics but I see and think about it along with the development

@see [JavScript Proxy Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy)
