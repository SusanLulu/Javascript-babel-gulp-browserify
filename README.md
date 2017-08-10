# Install Babel with Gulp, Browserify
Based on babel example

##### set up gulp globally

```
npm install -g gulp

gulp --version
```

##### start project

```
//1-1.save gulp in package.json 
npm install gulp --save-dev

//1-2.check in node_modules
ls node_modules
cat package.json

//1-3.edit gulpfile
vi gulpfile.js
gulp
mv gulpfile.js gulpfile.babel.js
npm install babel-core --save-dev

//1-4.check .babelrc
cat .babelrc
gulp

//2-1 add babel and browserify into gulp
npm install browserify babelify vinyl-source-stream --save -dev

//2-2 update gulp.babel.js & index.html
//2-3 mkdir src & mkdir dist
//2-4 rm app.js app.js.es6

//2-5 create new app.js & flash-message.js
gulp
ls dist/
cat dist/bundle.js
open index.html

```

###### Reference:
1.https://github.com/codeschool/babel-with-gulp

