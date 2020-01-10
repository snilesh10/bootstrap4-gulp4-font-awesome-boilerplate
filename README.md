# Bootstrap 4 Gulp 4 Sass Fontawesome 5 Boilerplate / Starter Template

Bootstrap 4 ,SASS,Fontawesome , Gulp development envioronment or boilerplate or starter template. Uses Bootstrap 4.4.1 , Gulp 4 , sass ,BrowserSync using NPM. 

Compile and minifies all the JS and CSS files inside /dist/ directory.

Feel Free to Fork, star or use it in your web development project.

## Requirements

- [Node.js with NPM](https://nodejs.org/en/download/ "Node Js")
- Gulp

## Getting started

1. Clone repository:

- `git clone https://github.com/snilesh10/bootstrap4-gulp4-font-awesome-boilerplate.git`

2. Change directory:

- `cd bootstrap4-gulp4-font-awesome-boilerplate`

3. Make sure Node and Gulp is already installed:
-  You can run `gulp -v` and `npm -v` to check. If not installed please install them.

3. Install all node modules:

- `npm install`

4. Install all devDependencies and dependencies:
- `npm install --save bootstrap`

- `npm install --save @fortawesome/fontawesome-free`

- `npm install --save jquery`

- `npm install --save popper.js`


5. Run Gulp Task:

- `gulp` - Compiles scss to css, minify css and js and builds apps ready for production into the **dist** folder.

- `gulp dev` - Starts localhost server with browser-sync, watches HTML, Sass, JS with hot reloading.

## Overwriting Bootstrap Variables in Sass

- `bootstrap4-gulp4-font-awesome-boilerplate/assets/scss/_bootstrap_variable_overrides.scss`

## Dependencies

```
 "devDependencies": {
    "browser-sync": "^2.26.7",
    "del": "^3.0.0",
    "gulp": "^4.0.2",
    "gulp-autoprefixer": "^4.1.0",
    "gulp-clean-css": "3.9.4",
    "gulp-concat": "^2.6.1",
    "gulp-html-replace": "^1.6.2",
    "gulp-rename": "^1.4.0",
    "gulp-sass": "^4.0.2",
    "gulp-sourcemaps": "^2.6.5",
    "gulp-uglify": "^3.0.2",
    "merge-stream": "^1.0.1"
  },
  "dependencies": {
    "@fortawesome/fontawesome-free": "^5.12.0",
    "bootstrap": "^4.4.1",
    "jquery": "^3.4.1",
    "popper.js": "^1.16.0"
  }
```
