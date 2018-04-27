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

1. Clone project with `git clone git@github.com:rodrigomata/sass-boilerplate.git``
2. Install `node-sass` dependencies with `npm i`

## Usage

1. Run your SASS compiler with `npm run compile:sass`
    - For SCSS style: `npm run compile:scss`
2. If you want to autocompile SASS and auto-reload the webpage to develop faster, use `npm run dev:sass`
3. A window will open with the project, if not, navigate to [http://localhost:8080](http://localhost:8080) to start working on it
3. Reference `dist/styles.css` in your html
3. (Optional) Run your Live server with `npm run dev:server`
4. (Optional) Minify assets and compile project with `npm run prod:build`

## Contribution

Please consider the following git styles for committs:

http://udacity.github.io/git-styleguide/

## License

MIT
