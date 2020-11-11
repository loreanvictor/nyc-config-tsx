# nyc-config-tsx

A default typescript configuration for test coverage using [nyc](https://github.com/istanbuljs/nyc),
which also properly instruments JSX files (see [this issue](https://github.com/istanbuljs/nyc/issues/1334)).

## Installation

```bash
npm i nyc-config-tsx --save-dev
```

### Usage

In `package.json`/`.nycrc`:

```json
"nyc": {
  "extends": "nyc-config-tsx",
  ...
}
```
