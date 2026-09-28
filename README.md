# flockr-v2

Small Go tool: declutter ~/Downloads in one command

Started as a weekend hack, grew on me.

## Features

- Groups files into folders by extension
- Skips hidden files and folders by default
- Single static binary, no runtime deps
- Dry-run prints the plan before moving anything

## Usage

```bash
./bin/flockr-v2 ~/Downloads --dry-run
./bin/flockr-v2 ~/Downloads
```

## Install

```bash
go build -o bin/ ./...
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── roadmap.md
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```

## License

MIT - see [LICENSE](LICENSE).
