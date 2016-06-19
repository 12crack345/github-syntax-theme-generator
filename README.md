# GitHub syntax theme generators

[![NPM version](https://img.shields.io/npm/v/github-syntax-theme-generator.svg)](https://www.npmjs.org/package/github-syntax-theme-generator)
[![Build Status](https://travis-ci.org/primer/github-syntax-theme-generator.svg?branch=master)](https://travis-ci.org/primer/github-syntax-theme-generator)

> The GitHub syntax theme generator will generate themes for multiple platforms based on the GitHub syntax theme.

## Install

All of the built themes in this package are distributed at separate repositories. It's recommended that you install one of these if you're looking for a specific theme.

### CSS
- [github-syntax-light]()
- [github-syntax-dark]()

### Ace
- [github-ace-light]()
- [github-ace-dark]()

### Atom
- [github-light-syntax]()
- [github-dark-syntax]()

### TextMate
- [github-textmate-light]()
- [github-textmate-dark]()


## Development

Clone this repository and after `npm install`. Run

```
$ npm run build
```

This will run the script that will build all the themes.

## Adapters

The theme adapters are located in `./lib/adapters/` directory. Each one will complete a specific task to build that theme.

## Contributing

If you would like to see the theme compiled for another platform, we welcome pull requests.

## License

[MIT](./LICENSE) &copy; [GitHub](https://github.com/)
