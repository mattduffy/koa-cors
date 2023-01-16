# My Koa App CORS Middleware

This package provides a simple interface to add and manage CORS rules for a list of endpoints in your Koa app.

## Using koa-cors

```bash
npm install --save-dev @mattduffy/koa-cors
```

```javascript
import cors from '@mattduffy/koa-cors'
const list = [
  {url, access},
  {url, access}
]
cors.endpoints(list)
app.use(cors)

```

...
