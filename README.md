# CSS COLUMN RULE WIDTH

  Mobile-first classes for css-column-rule-width.
  Set the desired css-column-rule-width on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-column-rule-width
```
View on [npm](https://www.npmjs.org/package/css-column-rule-width)


## File Size

2.1K column-rule-width.css
1.5K column-rule-width.min.css

## The Code
```
.crw-thin {   column-rule-width: thin; }
.crw-med {    column-rule-width: medium; }
.crw-thick {  column-rule-width: thick; }

.crw-1 {      column-rule-width: 1px; }
.crw-2 {      column-rule-width: 2px; }
.crw-3 {      column-rule-width: 3px; }
.crw-4 {      column-rule-width: 4px; }
.crw-5 {      column-rule-width: 5px; }
.crw-10 {     column-rule-width: 10px; }
.crw-20 {     column-rule-width: 20px; }

.crw-i {      column-rule-width: inherit; }

@media screen and (min-width: 48em) {
  .crw-thin-ns {   column-rule-width: thin; }
  .crw-med-ns {    column-rule-width: medium; }
  .crw-thick-ns {  column-rule-width: thick; }
  .crw-1-ns {      column-rule-width: 1px; }
  .crw-2-ns {      column-rule-width: 2px; }
  .crw-3-ns {      column-rule-width: 3px; }
  .crw-4-ns {      column-rule-width: 4px; }
  .crw-5-ns {      column-rule-width: 5px; }
  .crw-10-ns {     column-rule-width: 10px; }
  .crw-20-ns {     column-rule-width: 20px; }
  .crw-i-ns {      column-rule-width: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .crw-thin-m {   column-rule-width: thin; }
  .crw-med-m {    column-rule-width: medium; }
  .crw-thick-m {  column-rule-width: thick; }
  .crw-1-m {      column-rule-width: 1px; }
  .crw-2-m {      column-rule-width: 2px; }
  .crw-3-m {      column-rule-width: 3px; }
  .crw-4-m {      column-rule-width: 4px; }
  .crw-5-m {      column-rule-width: 5px; }
  .crw-10-m {     column-rule-width: 10px; }
  .crw-20-m {     column-rule-width: 20px; }
  .crw-i-m {      column-rule-width: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .crw-thin-l {   column-rule-width: thin; }
  .crw-med-l {    column-rule-width: medium; }
  .crw-thick-l {  column-rule-width: thick; }
  .crw-1-l {      column-rule-width: 1px; }
  .crw-2-l {      column-rule-width: 2px; }
  .crw-3-l {      column-rule-width: 3px; }
  .crw-4-l {      column-rule-width: 4px; }
  .crw-5-l {      column-rule-width: 5px; }
  .crw-10-l {     column-rule-width: 10px; }
  .crw-20-l {     column-rule-width: 20px; }
  .crw-i-l {      column-rule-width: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

