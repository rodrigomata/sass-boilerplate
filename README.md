![Build Status](https://travis-ci.org/rodrigomata/sass-boilerplate.svg?branch=master)[![Known Vulnerabilities](https://snyk.io/test/github/rodrigomata/sass-boilerplate/badge.svg?targetFile=package.json)](https://snyk.io/test/github/rodrigomata/sass-boilerplate?targetFile=package.json)

# SASS Boilerplate
SASS boilerplate project to quickly start developing, it follows the [7 in 1 Architecture](https://sass-guidelin.es/#architecture) to keep components isolated and a clean project structure.

## Requirements

- [NodeJS](https://nodejs.org/en/)

## Stack

- HTML5
- CSS3
- SASS
- NodeJS 8.x

### Development Dependencies

- [NodeSass 4.9.x](https://www.npmjs.com/package/node-sass)
- [Concurrently 3.5.x](https://www.npmjs.com/package/concurrently)
- [Liveserver 1.2.x](https://www.npmjs.com/package/live-server)

## Installation

1. Clone project with `git clone git@github.com:rodrigomata/sass-boilerplate.git`
2. Install `node-sass` dependencies with `npm i`

## Usage

Compile SASS and live server
------
If you want to autocompile SASS and auto-reload the webpage to develop faster, use `npm run dev`
- A window will open with the project, if not, navigate to [http://localhost:8080](http://localhost:8080) to start working on it
- Reference `dist/main.css` in your html

Compile only SASS
------
Run your SASS compiler with `npm run compile:sass`

Only watch for SASS changes
------
`npm run watch:sass`

Live server
------
`npm run dev:server`

Minify and compile project
------
`npm run prod:build`

## Contribution

Before committing be sure that you run `npm run test` and no errors are shown.

Consider the following git styles for commits:

http://udacity.github.io/git-styleguide/

## License

MIT
