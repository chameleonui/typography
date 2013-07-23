
# typography

Chameleon UI typography mixins and styles

## Installation

Install with [component](http://component.io):

    $ component install chameleonui/typography

## API

### Use flags

You can disable some typography features through "use-flags":

```
// By defualt all flags are enabled (true)
use-typography-headings = true|false;
use-typography-paragraph = true|false;
use-typography-inlines = true|false;
use-typography-lists = true|false;
use-typography-quotes = true|false;
use-typography-code = true|false;
use-typography-nice-amp = true|false;
use-typography-text-align = true|false;
```

### Variables

```
// -- headings
heading-margin = 0 0 (1/4) 0;
heading-font-family = Helvetica Neue, Helvetica, Arial, sans-serif;
heading-line-height = 1.2;
heading-font-weight = 700;
heading-color = #000;

heading-small-color = #999;
heading-small-font-weight = 400;
heading-small-font-size = 70%;

heading-link-color = #1e87eb;
heading-link-text-decoration = none;

heading-link-visited-color = darken(heading-link-color, 20%);
heading-link-visited-text-decoration = heading-link-text-decoration;

heading-link-hover-color = lighten(heading-link-color, 20%);
heading-link-hover-text-decoration = underline;

h1-font-size-px = 44px;
h2-font-size-px = 32px;
h3-font-size-px = 26px;
h4-font-size-px = 21px;
h5-font-size-px = 18px;
h6-font-size-px = 16px;

// -- paragraph
p-margin = 0 0 1 0;
p-text-indent = 0;

p-p-margin = 0 0 1 0;
p-p-text-indent = 0;

// -- inlines
abbr-border-color = #000;

marked-color = #000;
marked-bg-color = #ffff66;

ins-color = #e00;
del-color = #666;

small-font-size = 80%;

sub-sup-font-size = 75%;
sup-top = -0.5em
sub-bottom = -0.25em

// -- lists
dl-margin = 0 0 1 0;
dl-padding = 0;
dt-margin = 0;
dt-font-weight = 700;
dd-margin = 0 0 0 1;
dd-font-weight = 400;

dl-horizontal-dt-width = 25%;
dl-horizontal-gutter = 5%;

list-inline-gutter = 1em;

ul-margin = 0 0 1 2em;
ul-padding = 0;
ul-list-style-position = outside;

ol-margin = 0 0 1 2.4em;
ol-padding = 0;
ol-list-style-position = outside;

ol-multilevel-number-color = #000;
ol-multilevel-number-width = 4em;
ol-multilevel-number-gutter = .5em;
ol-multilevel-margin-left-nesting-levels = 3;
ol-multilevel-margin-left-nesting-base = 3em;
ol-multilevel-margin-left-nesting-add = 1em;

// -- quotes
q-font-style = italic;

blockquote-margin = 0 0 1 0;
blockquote-padding = 0 0 0 1;
blockquote-color = #000;
blockquote-border-color = #eee;
blockquote-border-style = solid;
blockquote-border-width = 0 0 0 2px;
blockquote-font-style = italic;
blockquote-font-weight = 400;

blockquote-small-color = #000;
blockquote-small-font-weight = 700;
blockquote-small-font-size = 16px;
blockquote-small-font-style = italic;
blockquote-small-before-content = "\2014 \0020";

// -- code
code-margin = 0;
code-padding = 0 .3ex;
code-font-family = Menlo, Monaco, Consolas, 'Courier New', monospace;
code-font-size = 14px;
code-line-height = 1.5;
code-color = #111;
code-bg = #f7f7f7;
code-border = 1px solid #e1e1e1;
code-border-radius = 3px;

pre-margin = 0 0 1 0;
pre-padding = 1ex;
pre-bg = code-bg;
pre-border = code-border;
pre-border-radius = 5px;
pre-color = code-color;
```


### Init

```
typography();
```

## Author(s)

Edgedesign s.r.o. – Tomas Kuba

## License

The MIT License (MIT)

Copyright © 2013 Edgedesign s.r.o.

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