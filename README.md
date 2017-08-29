# date-holidays-bundle-test

This is just a test package showing that the [date-holidays](https://github.com/commenthol/date-holidays) package will only work in a [browserify](http://browserify.org) bundle if all of the greek characters in the [astronomia](https://github.com/commenthol/astronomia) package are replaced with latin ones.

What I did was use my [greeklish-file-replace](https://github.com/kodie/greeklish-file-replace) package to create [this fork](https://github.com/kodie/astronomia) of the astronomia package. I then created [this fork](https://github.com/kodie/date-holidays) of the date-holidays package so that it uses my version of the astronomia package instead of the official one.

## Installation
```
git clone https://github.com/kodie/date-holidays-bundle-test.git
```

## Usage
```shell
# My version
npm run test

# Official version
npm run official
```

And then visit `index.html` in your favorite internet browser.
