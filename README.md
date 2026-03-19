<p align="left">
    <img width="1280" height="192" alt="DeclareUI" src="https://github.com/user-attachments/assets/d51c038f-7822-4ee4-beb8-f438894f7736#gh-light-mode-only" />
    <img width="1280" height="192" alt="DeclareUI" src="https://github.com/user-attachments/assets/44918531-3b1b-4ace-bca0-db0ea99f8bc8#gh-dark-mode-only" />
</p>

# create-declareui

Project scaffolding tool — bootstrap a new DeclareUI project with a single command.

---

## Usage

```bash
# npm
npx create-declareui my-design-system

# pnpm
pnpm create declareui my-design-system

# yarn
yarn create declareui my-design-system
```

## What it generates

```
my-design-system/
├── declareui.config.yaml     # Project configuration
├── src/
│   └── components/
│       ├── button.ui.yaml    # Example Button component
│       └── card.ui.yaml      # Example Card component
├── package.json
├── tailwind.config.js
└── tsconfig.json
```

## Options

```bash
create-declareui my-project [options]

Options:
  --targets <frameworks>   Target frameworks (react,vue,svelte,angular,wc)
  --typescript             Enable TypeScript (default: true)
  --tailwind               Include Tailwind CSS setup (default: true)
  --template <name>        Use a starter template
```

## Related packages

| Package | Description |
|:--------|:------------|
| [`@declareui/cli`](https://github.com/declare-ui/cli) | CLI tool for building and managing components |
| [`@declareui/core`](https://github.com/declare-ui/core) | Parser, AST, and code generators |
| [`@declareui/examples`](https://github.com/declare-ui/examples) | Example projects |

## Contributing

See [CONTRIBUTING.md](https://github.com/declare-ui/.github/blob/main/CONTRIBUTING.md) for guidelines.

## License

MIT
