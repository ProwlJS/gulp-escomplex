# Code Complexity Analysis for Gulp

This module does static analysis of source files and prepares them for a `reporter`.

It uses `escomplex` to do the heavy lifting.

```
gulp.task('complexity', function () {
  return gulp.src([
    'index.js',
    'gulpfile.js'
  ])
  .pipe(complexity());
});
```