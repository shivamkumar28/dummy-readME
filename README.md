# react-native-chucker

**react-native-chucker** simplifies the inspection of **HTTP(S) requests/responses** fired by your React Native App. **react-native-chucker** works as an **OkHttp Interceptor** persisting all those events inside your application, and providing a UI for inspecting and sharing their content.

Apps using **react-native-chucker** will display a **notification** showing a summary of ongoing HTTP activity. Tapping on the notification launches the full **react-native-chucker** UI. Apps can optionally suppress the notification, and launch the **react-native-chucker** UI directly from within their own interface.

## Installation

```sh
npm install react-native-chucker
```
 OR
```sh
yarn add react-native-chucker
```

## iOS

#### Install Dependencies

Insert the following lines inside the onCreate block in `MainApplication.java`:

    OkHttpClientProvider.setOkHttpClientFactory(new CustomNetworkModule(this));



## Usage

```js
import { ChuckerView } from "react-native-chucker";

// ...

<ChuckerView color="tomato" />
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT

---

Made with [create-react-native-library](https://github.com/callstack/react-native-builder-bob)
