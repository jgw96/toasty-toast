[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/jgw96/toasty-toast)

# Toasty Toast

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="toasty-toast.html">
    <toasty-toast open="true" message="hello world" duration="5000"></toasty-toast>
  </template>
</custom-element-demo>
```
-->
```
<toasty-toast></toasty-toast>
```

Toasty Toast is a simple Polymer 2.0 web component that gives you a nice little popup "toast" that can show a short
piece of information for a specified time. A good real world example of a toast can be found on inbox by gmail and a
multitude of Android apps.

### Note
This is built with Polymer 2.0 which is undergoing rapid development at the moment. I will do my hardest to
update this component as Polymer 2.0 changes. If you ever find it broken dont hesitate to open bugs (:

## Installation

install: `bower install toasty-toast --save`

import: `<link rel="import" href="bower_components/toasty-toast/toasty-toast.html">`

## Usage

`<toasty-toast>` expects three attributes: `duration`, `message` and `open`.
To open a toast simply set the open attribute to `"true"`, but before opening a toast
be sure to have set a duration and a message.

1. `duration`: number, example: `duration="3000"`
2. `message`: string, example: `message="hello world"`
3. `open`: boolean, example: `open="true"`

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT License

Copyright (c) 2016 Justin Willis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
