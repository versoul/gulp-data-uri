
> convert imgs from css to datauri

## Usage

First, install `gulp-data-uri` as a development dependency:

```shell
npm install gulp-data-uri --save-dev
```

Then, add it to your `gulpfile.js`:

```javascript
var data_uri = require('gulp-data-uri');

gulp.task('templates', function(){
  gulp.src(['file.txt'])
    .pipe(data_uri())
    .pipe(gulp.dest('build/file.txt'));
});
```
