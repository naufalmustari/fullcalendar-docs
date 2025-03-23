
# FullCalendar Docs

This repo contains the static content for [https://github.com/naufalmustari/fullcalendar-docs/releases](https://github.com/naufalmustari/fullcalendar-docs/releases)

Documentation articles are found in directories like `_docs-*`.

Made with [Jekyll](https://github.com/naufalmustari/fullcalendar-docs/releases).


## Reporting Problems

See a problem with the docs? Create a ticket in the [main dev repo's issue tracker](https://github.com/naufalmustari/fullcalendar-docs/releases). All docs-related bugs have the [docs label](https://github.com/naufalmustari/fullcalendar-docs/releases%3Aopen+is%3Aissue+label%3ADocs).


## Installation

Clone this repo:

```sh
git clone https://github.com/naufalmustari/fullcalendar-docs/releases
cd fullcalendar-docs
```

Prerequisites:

- NPM / PNPM
- Ruby 2.x
- [Rubygem bundler](https://github.com/naufalmustari/fullcalendar-docs/releases) (`gem install bundler`)


## CLI

```sh
npm install

# watch & serve while developing
npm run dev

# build into _site directory
npm run build
```


## Contributing

To make edits to the documentation please submit a [Pull Request](https://github.com/naufalmustari/fullcalendar-docs/releases) against the `main` branch of this repo.

Ensure linting passes before submitting PRs:

```sh
npm run lint
```
