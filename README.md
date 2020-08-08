# \<lit-number-stepper>

A LitElement Web Component providing a number counter with icon buttons to increment and decrement the counter value. This webcomponent follows the [open-wc](https://github.com/open-wc/open-wc) recommendation.

## Installation
```bash
npm i lit-number-stepper
```

## Usage
```html
<script type="module">
  import 'lit-number-stepper/lit-number-stepper.js';
</script>

<lit-number-stepper></lit-number-stepper>
```

## Properties

#### `counter: number`

Number being incremented and decremented. Defaults to `0`.

#### `minimum: number`

Lowest allowable number. Defaults to `0`.

#### `maximum: number`

Highest allowable number. Defaults to `null` (no maximum).

## CSS Custom Properties

#### `--lit-number-stepper-text-color`

Text color of counter value. Default is `#000`.

#### `--lit-number-stepper-icon-color`

Color of increment and decrement icon buttons. Default is `#000`.

#### `--lit-number-stepper-icon-size`

Size of increment and decrement icon buttons. Default is `36px`.

#### `--lit-number-stepper-font-size`

Size of counter text. Default is `medium`.

#### `--lit-number-stepper-font-family`

Font family for counter text. Default is `Arial, Helvetica, sans-serif`

## Linting with ESLint, Prettier, and Types
To scan the project for linting errors, run
```bash
npm run lint
```

You can lint with ESLint and Prettier individually as well
```bash
npm run lint:eslint
```
```bash
npm run lint:prettier
```

To automatically fix many linting errors, run
```bash
npm run format
```

You can format using ESLint and Prettier individually as well
```bash
npm run format:eslint
```
```bash
npm run format:prettier
```


## Tooling configs

For most of the tools, the configuration is in the `package.json` to reduce the amount of files in your project.

If you customize the configuration a lot, you can consider moving them to individual files.

## Local Demo with `es-dev-server`
```bash
npm start
```
To run a local development server that serves the basic demo located in `demo/index.html`
