## Register provider

Like any other provider, you need to register the shield provider inside `start/app.js` file.

```js
const providers = [
  'adonis-shield-no-session/providers/ShieldProvider'
]
```

## Register middleware

Next step is to register the middleware inside `start/kernel.js` file.

```js
const globalMiddleware = [
  'CrBast/Middleware/Shield-No-Session'
]
```

## Dependencies

This module only use `ViewProvider`.


## Config

The configuration is saved inside `config/shield.js` file. Tweak it accordingly.
