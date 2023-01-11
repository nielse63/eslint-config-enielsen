# eslint-config-enielsen

[![node](https://github.com/nielse63/eslint-config-enielsen/actions/workflows/node.js.yml/badge.svg)](https://github.com/nielse63/eslint-config-enielsen/actions/workflows/node.js.yml) ![David](https://img.shields.io/david/nielse63/eslint-config-enielsen)

> Personal ESLint config settings

<div style="display:flex;align-items:center;justify-content:space-around">
<img src="docs/img/eslint.png">
<img src="docs/img/prettier.png">
<img src="docs/img/jest.png">
</div>

## Intro

`eslint-config-enielsen` is a light-as-hell GitHub template repo to quickly and easily get a new Node.js project up and running. It's meant to be a skeleton for future projects and framework/feature agnostic - whether you want to create an Express app, CLI tool, or just a quick script `eslint-config-enielsen` is a good starting point.

## Features

- Linting - `eslint-config-airbnb-base` setup by default
- Code Formatting - `prettier` and `eslint` formatting options enabled
- Node Versioning - `.nvmrc` set to latest LTS
- Testing - Minimal `jest` configuration setup
- CI/CD - Skeleton GitHub Actions included
- Community Files - GitHub community files are created by default

## Installation

1. Click [Use this template](https://github.com/nielse63/eslint-config-enielsen/generate) at the top of the eslint-config-enielsen GitHub repo
2. Clone your project
3. Run `npm run setup` - you'll be prompted for new values
4. **Optional**: After you completed the setup run `rm -rf .bin/cli`

## Usage

After you've run the setup script, you're ready to start developing. The structure and content is like any normal basic node.js app:

```
.
├── .bin            # scripts and tooling
├── .github         # github workflows and templates
├── .husky          # git hooks configuration
├── docs            # github-pages docs
├── index.js        # main entry
└── src             # source file directory
    ├── __tests__   # tests
    └── index.js    # main source entry
```

### Scripts

There are a number of useful npm scripts:

| Script            | Description                                       |
| ----------------- | ------------------------------------------------- |
| `npm run setup`   | Installs dependencies and configures the app info |
| `npm run test`    | Run Jest unit tests                               |
| `npm run lint`    | Check and fix all files using ESLint and Prettier |
| `npm run release` | Release a new version of the app                  |

## Roadmap

I'm planning on adding the following feature enhancements soon:

- [ ] Automated doc generation
- [ ] Script to auto-generate jest tests
- [ ] More GitHub actions and workflows
- [ ] Improved documentation
