# Google Test Task

## Project description

This project completed with `postcss` plugin (`autoprefixer` and `cssnano`). We compile `style.src.css` to `style.dist.css`, which located in `assets/css` directory. HTML markup completed with use BEM metodology.

## Npm scripts:

`npm run build`: compile `assets/css/style.src.css` to `assets/css/style.dist.css`. We use `postcss` with `autoprefixer` and `cssnano`.

`npm run watch`: watch changes.

`npm run server`: start live-server.

`npm start`: start `watch` and `server` npm scripts with use `npm-run-all` plugin. This plugin can start some scripts parallely.
