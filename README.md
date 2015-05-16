# tooltip.css

[![NPM version][npm-img]][npm-url]
[![License][license-img]][license-url]

A simple CSS tooltip.

## Installation

```
npm install tooltip.css
```

## Usage

### CSS

``` css
@import "tooltip.css";

:root {
  --tt-transition:      opacity 0.2s ease-in;
  --tt-colorBackground: #111;
  --tt-colorForeground: #ddd;
  --tt-borderRadius:    0;
  --tt-opacity:         1;
}
```

### HTML

``` html
<p>
  This is a <span class="tooltip tooltip--top tooltip__skin tooltip__skin--top" data-tooltip="This is a tooltip">sentence</span>.
</p>
```

### Extending

You can use modifier classes to adjust properties:

``` css
.tooltip--small::before {
  font-size: 0.75rem;
}
```

[npm-img]: https://img.shields.io/npm/v/tooltip.css.svg?style=flat-square
[npm-url]: https://npmjs.org/package/tooltip.css
[license-img]: http://img.shields.io/npm/l/tooltip.css.svg?style=flat-square
[license-url]: LICENSE
