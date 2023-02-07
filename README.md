# React17-Intl-Tel-Input

## Original Demo & Examples

Live demo: [patw0929.github.io/react-intl-tel-input](https://patw0929.github.io/react-intl-tel-input/)

To build the examples locally, run:

```bash
yarn
yarn website:start
```

Then open [`localhost:3000`](http://localhost:3000) in a browser.

## Installation

```bash
yarn add react17-intl-tel-input
```

### TypeScript

`react17-intl-tel-input` ships with official type declarations out of the box.

## Usage

```javascript
import IntlTelInput from 'react17-intl-tel-input'
import 'react17-intl-tel-input/dist/main.css'

;<IntlTelInput
  containerClassName="intl-tel-input"
  inputClassName="form-control"
/>
```

### Properties

Please see the original [Demo Page](https://patw0929.github.io/react-intl-tel-input/)

## Development (`src` and the build process)

To build, watch and serve the examples (which will also watch the component source), run `yarn website:start`.

You can prepare a distribution build using `yarn build`.

## Contributing

Any kind of contribution including proposals, doc improvements, enhancements, bug fixes are always welcome.

To contribute to `react17-intl-tel-input`, clone this repo locally and commit your code on a separate branch. Please write tests for your code, and run the linter before opening a pull-request:

```bash
yarn test    # if you are enhancing the JavaScript modules
yarn test:ts # if you are enhancing the TypeScript type declarations
yarn lint
```

Also, please let us know if you encounter any issue by filing an [issue](https://github.com/jd-oconnor/react-intl-tel-input/issues)

## Inspired by

[react-intl-tel-input](https://github.com/patw0929/react-intl-tel-input) - [@patw0929](https://github.com/patw0929)

[International Telephone Input](https://github.com/jackocnr/intl-tel-input) - [@jackocnr](https://github.com/jackocnr)

## License

MIT
