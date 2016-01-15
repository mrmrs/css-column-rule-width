# css-column-rule-width 0.0.7

Css module of single purpose classes for column rule width

#### Stats

332 | 44 | 44
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-rule-width
```

#### With Git

```
git clone https://github.com/tachyons-css/css-column-rule-width
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-rule-width";
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
<link rel="stylesheet" href="path/to/module/css/css-column-rule-width">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   COLUMN RULE WIDTH
*/
.crw-thin { column-rule-width: thin; }
.crw-med { column-rule-width: medium; }
.crw-thick { column-rule-width: thick; }
.crw-1 { column-rule-width: 1px; }
.crw-2 { column-rule-width: 2px; }
.crw-3 { column-rule-width: 3px; }
.crw-4 { column-rule-width: 4px; }
.crw-5 { column-rule-width: 5px; }
.crw-10 { column-rule-width: 10px; }
.crw-20 { column-rule-width: 20px; }
.crw-i { column-rule-width: inherit; }
@media screen and (min-width: 48em) {
 .crw-thin-ns { column-rule-width: thin; }
 .crw-med-ns { column-rule-width: medium; }
 .crw-thick-ns { column-rule-width: thick; }
 .crw-1-ns { column-rule-width: 1px; }
 .crw-2-ns { column-rule-width: 2px; }
 .crw-3-ns { column-rule-width: 3px; }
 .crw-4-ns { column-rule-width: 4px; }
 .crw-5-ns { column-rule-width: 5px; }
 .crw-10-ns { column-rule-width: 10px; }
 .crw-20-ns { column-rule-width: 20px; }
 .crw-i-ns { column-rule-width: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .crw-thin-m { column-rule-width: thin; }
 .crw-med-m { column-rule-width: medium; }
 .crw-thick-m { column-rule-width: thick; }
 .crw-1-m { column-rule-width: 1px; }
 .crw-2-m { column-rule-width: 2px; }
 .crw-3-m { column-rule-width: 3px; }
 .crw-4-m { column-rule-width: 4px; }
 .crw-5-m { column-rule-width: 5px; }
 .crw-10-m { column-rule-width: 10px; }
 .crw-20-m { column-rule-width: 20px; }
 .crw-i-m { column-rule-width: inherit; }
}
@media screen and (min-width: 64em) {
 .crw-thin-l { column-rule-width: thin; }
 .crw-med-l { column-rule-width: medium; }
 .crw-thick-l { column-rule-width: thick; }
 .crw-1-l { column-rule-width: 1px; }
 .crw-2-l { column-rule-width: 2px; }
 .crw-3-l { column-rule-width: 3px; }
 .crw-4-l { column-rule-width: 4px; }
 .crw-5-l { column-rule-width: 5px; }
 .crw-10-l { column-rule-width: 10px; }
 .crw-20-l { column-rule-width: 20px; }
 .crw-i-l { column-rule-width: inherit; }
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

