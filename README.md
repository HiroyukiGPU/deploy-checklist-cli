# Deploy Checklist

Run configurable pre-deployment checks.

## Requirements

Node.js 22 or newer.

## Install

```sh
npm install
npm run build
npm link
```

## Usage

```sh
deploy-check --help
deploy-check --version
```

Destructive operations require explicit confirmation such as `--yes`; file organization defaults to preview mode. Secret-looking values are masked.

## Development

```sh
npm run lint
npm test
npm run build
```

## License

MIT
