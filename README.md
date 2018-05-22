# Reddit Redesign

Recreating the new Reddit Redesign

### Version

0.0.1

## Install Dependencies

```bash
npm install
```

## Compile Sass & Run Dev Server

gulp

```bash
gulp
```
OR

```bash
npm start
```

## Folder and File Structure

/src
    /css
    styles.css
        /vendor
        -font-awesome.min.css
    /fonts
    -fontawesome-webfont.eot
    -fontawesome-webfont.svg
    -fontawesome-webfont.ttf
    -fontawesome-webfont.wotf
    -fontawesome-webfont.wotf2
    -FontAwesome.otf
    /img
    /js
        -index.js
        -main.js
    /scss
    -styles.scss
-index.html
-gulpfile.js
-LICENSE
-package.json
-readme.md

## Bundle and minify compiled CSS and JS

```bash
gulp useref
```

## Bulid to dist from src

```bash
gulp build
```
## Clean (delete) dist

```bash
gulp clean:dist
```

## Features:

* Bootstrap 4
* FontAwesome 5


## Future Features:

* Infinite Scroll (no footer needed)
* 

## Known "bugs"


#### Change Log

###### 0.0.1

* initial setup and commit
