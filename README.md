# Zeitgeist Documentation

[![Crowdin](https://badges.crowdin.net/zeitgeist-documentation/localized.svg)](https://crowdin.com/project/zeitgeist-documentation)

This website is built using [Docusaurus 2](https://v2.docusaurus.io/), a modern
static website generator.

## Contributing

The Zeitgeist Documentation is maintained by
[zeitgeistpm](https://github.com/zeitgeistpm), but community contributions are
very welcome. Please refer to [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

## Deployment

### Installation

```console
yarn install
```

### Local Development Server

```console
yarn start
```

This command starts a local development server and open up a browser window.
Most changes are reflected live without having to restart the server.

### Build

```console
yarn build
```

This command generates static content into the `build` directory and can be
served using any static contents hosting service.

### Deployment

```console
GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to
build the website and push to the `gh-pages` branch.

## Formatting Markdown

This repository uses `prettier` to maintain a consistent code style. After
writing the content, you can use the `yarn fmt` script to format the markdown
using `prettier`.
