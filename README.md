## @gpsgate/react-native-cookies

@gpsgate/react-native-cookies

### Installation

```
yarn add git+https://github.com/gpsgate/react-native-cookies.git
```

### Usage

```js
import CookieManager from "@gpsgate/react-native-cookies";

// Clear all cookies
await CookieManager.clearAll();

// Get all cookies for the specified domain
const cookies = await CookieManager.get("https://domain");
```
