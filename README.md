# css-font-style 0.0.7

Css module of single purpose classes for font style

#### Stats

186 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-font-style
```

#### With Git

```
git clone https://github.com/tachyons-css/css-font-style
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-font-style";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-font-style">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FONT STYLE
*/
.fsn { font-style: normal; }
.i { font-style: italic; }
.oblique { font-style: oblique; }
@media screen and (min-width: 48em) {
 .fsn-ns { font-style: normal; }
 .i-ns { font-style: italic; }
 .oblique-ns { font-style: oblique; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .fsn-m { font-style: normal; }
 .i-m { font-style: italic; }
 .oblique-m { font-style: oblique; }
}
@media screen and (min-width: 64em) {
 .fsn-l { font-style: normal; }
 .i-l { font-style: italic; }
 .oblique-l { font-style: oblique; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

