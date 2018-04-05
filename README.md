The following error occurs when removing views from portal:

```
TypeError: undefined is not an object (evaluating 'children.indexOf')

This error is located at:
    in Modal (at App.js:83)
    in RCTView (at View.js:78)
    in View (at App.js:80)
    in SomeChild (at App.js:56)
    in MyApp (at App.js:35)
    in RCTView (at View.js:78)
    in View (at App.js:32)
    in App (at registerRootComponent.js:35)
    in RootErrorBoundary (at registerRootComponent.js:34)
    in ExpoRootComponent (at renderApplication.js:35)
    in RCTView (at View.js:78)
    in View (at AppContainer.js:102)
    in RCTView (at View.js:78)
    in View (at AppContainer.js:122)
    in AppContainer (at renderApplication.js:34)
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:13603:27 in removeChild
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:10555:22 in unmountHostComponents
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:10599:26 in commitDeletion
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:11444:25 in commitAllHostEffects
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:39:15 in invokeGuardedCallback
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:221:34 in invokeGuardedCallback
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:11546:32 in commitRoot
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:12795:46 in completeRoot
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:12745:23 in performWorkOnRoot
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:12660:26 in performWork
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:12622:16 in performSyncWork
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:12535:6 in requestWork
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:12374:22 in scheduleWorkImpl
- node_modules/react-native/Libraries/Renderer/ReactNativeRenderer-dev.js:6388:19 in enqueueSetState
- node_modules/react/cjs/react.development.js:242:31 in setState
* App.js:74:20 in <unknown>
```
