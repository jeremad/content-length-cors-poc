## POC for https://github.com/mdn/browser-compat-data/pull/15027

### How to use?

Run
```js
npx http-server
```
Connect to the browser of your choice with the developer tools console to `127.0.0.1:8181`.

If `null` is displayed it means that the browser does not consider `content-length` a CORS-safelisted response header.
