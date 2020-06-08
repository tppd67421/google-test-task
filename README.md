# Google Test Task

## Project description

This project completed with `postcss` plugin (`autoprefixer` and `cssnano`). `style.src.css` is compiled to `style.dist.css`, which located in `assets/css` directory. HTML markup done using BEM metodology.

## Npm scripts:

`npm run build`: compile `assets/css/style.src.css` to `assets/css/style.dist.css`. `postcss` is used with `autoprefixer` and `cssnano`.

`npm run watch`: watch changes.

`npm run server`: start live-server.

`npm start`: start `watch` and `server` npm scripts with use `npm-run-all` plugin. This plugin can start some scripts parallely.
