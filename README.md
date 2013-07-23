# Sassline

Set text on the web to a baseline grid easily with rems and Sass. A starting point for prototyping, blogs or other web projects with base typography styling and no bloat.

## Do one thing well

There are many different options when it comes to boilerplates, frameworks and pattern libraries these days. Sassline has one aim and one aim only – to spread better typography across the responsive environment that is the web.

The idea is to have easy to use and maintain SCSS files utilising the power of Sass to speed up the, sometimes, complex calculations to set type on a baseline grid with a production ready CSS output. Using rems for the font-sizing and the spacing measurements gives a simple way to use the proportions of the baseline grid throughout the design.

OpenType features are enabled to give the nicest formatting of text and some flourishes in the headings if available in the web font (and supported in the browser).

Fallback pixel values are provided to use if desired for full browser support – see [here](http://caniuse.com/rem) for more info.

## Font-size = line-height?

Sassline is based on setting the root font-size as half the line-height of the paragraph text. The height of the baseline grid is then effectively set at 2rem. The styling included sets all the typographic elements to the baseline and takes into account element ordering, i.e. if there is a h2 followed by an h3. The spacing is set between elements with the Gestalt law of proximity (elements closer together are visually grouped).

## Why?

I recently wrote a dissertation on responsive typography, looking at which historical typographic conventions are best suited to text in a responsive environment. Sassline takes some of my thoughts from this and puts them into action. You can also read some more about how it came about [here](http://typenot.es/posts/baseline-rems).

## Documentation

I am currently working on some more thorough documentation for Sassline, please check out the blog post [here](http://typenot.es/posts/baseline-rems) for now.

## Responsive Nav

Viljami Salminen’s [responsive-nav.js](https://github.com/viljamis/responsive-nav.js) plugin is included to provide a mobile ready navigation to work from.

========

## License

The MIT License (MIT)

Copyright (c) 2013 Jake Giltsoff

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.