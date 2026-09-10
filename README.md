# cliparse-hq

Small TypeScript CLI: CSV to JSON converter

Started as a weekend hack, grew on me.

## Getting started

```bash
npm install
npm run build
```

## Features

- commander-based subcommands
- Strict tsconfig, no any
- npm link friendly
- Ships as an ESM binary

## How to use

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```

## License

MIT - see [LICENSE](LICENSE).
