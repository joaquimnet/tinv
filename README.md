# tinv

<img src="https://raw.githubusercontent.com/joaquimnet/tinv/master/tinv.png" alt="dotenv" align="right" />

Just a simple genie for loading `.env` files.

### Install

```bash
npm i tinv
```

Or if you're using yarn:

```bash
yarn add tinv
```

### Use

Will check if there is an `.env` file (or `.env.dev` file) in your project root.

```js
require('tiny-env')();
// or
require('tiny-env')('.env.dev');
// or
require('tiny-env')('.env.your_custom_name');
// or
require('tiny-env')('../path/to/dot/.env');
```

### Tests

Run `yarn test` or `npm test`
