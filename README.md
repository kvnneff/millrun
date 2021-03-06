# millrun

> A writing app for your lumps.

![lsp](assets/lsp.gif)

## About

millrun is an [electron](http://electron.atom.io) app for writing drafts of articles, books, etc.

The features are limited! The design is simple! The goal is ambitious!

**Learn more at the website: [millrun.civicmakerlab.com](http://millrun.civicmakerlab.com)**

![screenshot](assets/screenshot.png)

## The goal
Provide the best experience for drafting prose.

## Current features

Create new drafts and edit them. That's it.

## Planned features

- `delete draft` button
- export as md, html, json, pdf
- save to github, dropbox, s3
- version drafts
  - include a version message
  - triggered by `save draft` button or `command+s`
- track all changes as operations. a version is a collection of operations.
- yaml front matter or other metadata editing approach
- create api/auth server
- create api clients for integrating with other projects
- sync with remote server
- create web version of editor

## Installation

You can install via the website: [millrun.civicmakerlab.com](http://millrun.civicmakerlab.com)

Or you can install the app as a command-line tool using npm:

```sh
npm install -g millrun
```

## Usage

If you've installed millrun as a command-line tool, start the app by running the `millrun` command:

```sh
millrun
```

Otherwise, if you downloaded the OSX build of the app, just double click the app and off you go.

## License
MIT
