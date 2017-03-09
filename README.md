# dist-server

> A basic express server for production build apps that was generated from [vue-loader](https://github.com/vuejs/vue-loader) or [create-react-app](https://github.com/facebookincubator/create-react-app).

## Usage

- Copy `server.js` to your project that has been created by *vue-loader* or *create-react-app*.
- Build the production version `npm run build` and make sure `server.js` serves from the correct folder (`dist` by default).
- Update `scripts` section in `package.json`.
- Install dependencies:

``` bash
$ npm i -S compression express helmet morgan
```
OR if you use `yarn`
``` bash
$ yarn add compression express helmet morgan
```

### Fork It And Make Your Own

You can fork this repo to create your own server.js boilerplate.