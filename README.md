# gulp-elm-test
Gulp plugin for running [elm-test](https://github.com/deadfoxygrandpa/elm-test).

## Install
```
$ npm install --save-dev gulp-elm-test
```

## Usage
```JavaScript
const gulp = require('gulp');
const elmTest = require('gulp-elm-test');

gulp.task('test', () => {
  return gulp.src('test/*Test.elm')
    .pipe(elmTest());
});
```
