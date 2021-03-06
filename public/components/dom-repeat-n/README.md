[![Bower version](https://badge.fury.io/bo/dom-repeat-n.svg)](https://badge.fury.io/bo/iron-swipeable-pages)
[![Build Status](https://travis-ci.org/MeTaNoV/dom-repeat-n.svg?branch=master)](https://travis-ci.org/MeTaNoV/iron-swipeable-pages)
[![Dependency Status](https://gemnasium.com/MeTaNoV/dom-repeat-n.svg)](https://gemnasium.com/MeTaNoV/iron-swipeable-pages)

A template element that repeat `n` times its content.

## Demo

[https://metanov.github.io/dom-repeat-n/](https://metanov.github.io/dom-repeat-n/components/dom-repeat-n/demo/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install dom-repeat-n --save
```

## Usage

Import Custom Element:

```html
<link rel="import" href="bower_components/dom-repeat-n/dom-repeat-n.html">
```

And then use it:

```html
<template is="dom-repeat-n" count="3">
  <div>I am div {{index}}</div>
</template>
```

See the [Documentation](https://metanov.github.io/dom-repeat-n/) for more options.

## Discussing

If you have any questions, you can find me on the [Polymer Slack Channel](https://polymer.slack.com/), or just raise an Issue.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT) © Pascal Gula

[![Throughput Graph](https://graphs.waffle.io/MeTaNoV/dom-repeat-n/throughput.svg)](https://waffle.io/MeTaNoV/dom-repeat-n/metrics)

