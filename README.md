# Request Axios

Proxy axios with human-friendly error.

## Install

```
npm i axios request-axios
```

Note: `axios` is a peer dependency, so you have to install it in your project.

## Usage

```
const request = require('request-axios')

await request({
  url: ...,
  method: ...,
  data: ...,
  ...
})
```

## License

MIT
