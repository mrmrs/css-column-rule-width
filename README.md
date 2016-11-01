# css-column-rule-width 1.0.6

Css module of single purpose classes for column rule width

#### Stats

434 | 44 | 132
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-rule-width
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-column-rule-width
```

ssh:
```
git clone git@github.com:tachyons-css/css-column-rule-width.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-rule-width";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-column-rule-width@1.0.6/css/css-column-rule-width.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-column-rule-width">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   COLUMN RULE WIDTH
*/
.crw-thin { -webkit-column-rule-width: thin; -moz-column-rule-width: thin; column-rule-width: thin; }
.crw-med { -webkit-column-rule-width: medium; -moz-column-rule-width: medium; column-rule-width: medium; }
.crw-thick { -webkit-column-rule-width: thick; -moz-column-rule-width: thick; column-rule-width: thick; }
.crw-1 { -webkit-column-rule-width: 1px; -moz-column-rule-width: 1px; column-rule-width: 1px; }
.crw-2 { -webkit-column-rule-width: 2px; -moz-column-rule-width: 2px; column-rule-width: 2px; }
.crw-3 { -webkit-column-rule-width: 3px; -moz-column-rule-width: 3px; column-rule-width: 3px; }
.crw-4 { -webkit-column-rule-width: 4px; -moz-column-rule-width: 4px; column-rule-width: 4px; }
.crw-5 { -webkit-column-rule-width: 5px; -moz-column-rule-width: 5px; column-rule-width: 5px; }
.crw-10 { -webkit-column-rule-width: 10px; -moz-column-rule-width: 10px; column-rule-width: 10px; }
.crw-20 { -webkit-column-rule-width: 20px; -moz-column-rule-width: 20px; column-rule-width: 20px; }
.crw-i { -webkit-column-rule-width: inherit; -moz-column-rule-width: inherit; column-rule-width: inherit; }
@media screen and (min-width: 48em) {
 .crw-thin-ns { -webkit-column-rule-width: thin; -moz-column-rule-width: thin; column-rule-width: thin; }
 .crw-med-ns { -webkit-column-rule-width: medium; -moz-column-rule-width: medium; column-rule-width: medium; }
 .crw-thick-ns { -webkit-column-rule-width: thick; -moz-column-rule-width: thick; column-rule-width: thick; }
 .crw-1-ns { -webkit-column-rule-width: 1px; -moz-column-rule-width: 1px; column-rule-width: 1px; }
 .crw-2-ns { -webkit-column-rule-width: 2px; -moz-column-rule-width: 2px; column-rule-width: 2px; }
 .crw-3-ns { -webkit-column-rule-width: 3px; -moz-column-rule-width: 3px; column-rule-width: 3px; }
 .crw-4-ns { -webkit-column-rule-width: 4px; -moz-column-rule-width: 4px; column-rule-width: 4px; }
 .crw-5-ns { -webkit-column-rule-width: 5px; -moz-column-rule-width: 5px; column-rule-width: 5px; }
 .crw-10-ns { -webkit-column-rule-width: 10px; -moz-column-rule-width: 10px; column-rule-width: 10px; }
 .crw-20-ns { -webkit-column-rule-width: 20px; -moz-column-rule-width: 20px; column-rule-width: 20px; }
 .crw-i-ns { -webkit-column-rule-width: inherit; -moz-column-rule-width: inherit; column-rule-width: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .crw-thin-m { -webkit-column-rule-width: thin; -moz-column-rule-width: thin; column-rule-width: thin; }
 .crw-med-m { -webkit-column-rule-width: medium; -moz-column-rule-width: medium; column-rule-width: medium; }
 .crw-thick-m { -webkit-column-rule-width: thick; -moz-column-rule-width: thick; column-rule-width: thick; }
 .crw-1-m { -webkit-column-rule-width: 1px; -moz-column-rule-width: 1px; column-rule-width: 1px; }
 .crw-2-m { -webkit-column-rule-width: 2px; -moz-column-rule-width: 2px; column-rule-width: 2px; }
 .crw-3-m { -webkit-column-rule-width: 3px; -moz-column-rule-width: 3px; column-rule-width: 3px; }
 .crw-4-m { -webkit-column-rule-width: 4px; -moz-column-rule-width: 4px; column-rule-width: 4px; }
 .crw-5-m { -webkit-column-rule-width: 5px; -moz-column-rule-width: 5px; column-rule-width: 5px; }
 .crw-10-m { -webkit-column-rule-width: 10px; -moz-column-rule-width: 10px; column-rule-width: 10px; }
 .crw-20-m { -webkit-column-rule-width: 20px; -moz-column-rule-width: 20px; column-rule-width: 20px; }
 .crw-i-m { -webkit-column-rule-width: inherit; -moz-column-rule-width: inherit; column-rule-width: inherit; }
}
@media screen and (min-width: 64em) {
 .crw-thin-l { -webkit-column-rule-width: thin; -moz-column-rule-width: thin; column-rule-width: thin; }
 .crw-med-l { -webkit-column-rule-width: medium; -moz-column-rule-width: medium; column-rule-width: medium; }
 .crw-thick-l { -webkit-column-rule-width: thick; -moz-column-rule-width: thick; column-rule-width: thick; }
 .crw-1-l { -webkit-column-rule-width: 1px; -moz-column-rule-width: 1px; column-rule-width: 1px; }
 .crw-2-l { -webkit-column-rule-width: 2px; -moz-column-rule-width: 2px; column-rule-width: 2px; }
 .crw-3-l { -webkit-column-rule-width: 3px; -moz-column-rule-width: 3px; column-rule-width: 3px; }
 .crw-4-l { -webkit-column-rule-width: 4px; -moz-column-rule-width: 4px; column-rule-width: 4px; }
 .crw-5-l { -webkit-column-rule-width: 5px; -moz-column-rule-width: 5px; column-rule-width: 5px; }
 .crw-10-l { -webkit-column-rule-width: 10px; -moz-column-rule-width: 10px; column-rule-width: 10px; }
 .crw-20-l { -webkit-column-rule-width: 20px; -moz-column-rule-width: 20px; column-rule-width: 20px; }
 .crw-i-l { -webkit-column-rule-width: inherit; -moz-column-rule-width: inherit; column-rule-width: inherit; }
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

ISC

