# Yeoman Foundation Generator

[Yeoman](http://yeoman.io) generator for [Zurb Foundation](http://foundation.zurb.com/) with:

* Foundation 6
* Sass compiling (LibSass / Compass options)
* Browserify dependency bundling
* Gulp automation
* Babel for ECMAScript 6 via the [ES2015 preset](http://babeljs.io/docs/plugins/preset-es2015/)
* BrowserSync server with live reloading
* Bourbon mixin library (option)
* Jade templating engine (option)
* Font Awesome (option)

## Getting Started

If Yeoman isn't already installed:
```
npm install -g yo
```

Install the generator from [npm](https://www.npmjs.com/package/generator-gulp-foundation-sass-babel-browserify):
```
npm install -g generator-gulp-foundation-sass-babel-browserify
```

Navigate to your target directory and initiate the generator:
```
yo gulp-foundation-sass-babel-browserify
```

Run `gulp` to start the server and watch for changes:
```
gulp
```

Include the `--prod` flag to export production-ready minified files (note: increases gulp task time, leave off for dev purposes):
```
gulp --prod
```

## Editing

Edit html/jade, scss and js files in the `src` directory

Gulp will serve finalized versions to the `build` directory

## License

MIT
