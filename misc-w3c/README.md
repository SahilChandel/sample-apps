# Miscellaneous W3C APIs
Various potentially useful APIs

- use vibration, [ref](https://developer.mozilla.org/en-US/docs/Web/API/Vibration_API)
- query available storage size, [ref](https://developer.mozilla.org/en-US/docs/Web/API/StorageManager/estimate)
- query available RAM, [ref](https://developer.mozilla.org/en-US/docs/Web/API/Performance/memory)
- query network connection status, [ref](https://developer.mozilla.org/en-US/docs/Web/API/Network_Information_API)
- query number of logical processors, [ref](https://developer.mozilla.org/en-US/docs/Web/API/NavigatorConcurrentHardware/hardwareConcurrency)
- access storage API, [ref](https://developer.mozilla.org/en-US/docs/Web/API/Storage_API)
- query camera capabilities, [ref](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getSupportedConstraints)

```js
  // vibrate once
  window.navigator.vibrate([200]);
  // vibrate a sequence
  window.navigator.vibrate([200, 400, 200, 200, 200]);
````