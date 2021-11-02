# marko-perfect-scrollbar
Auto-Scoll for MarkoJS component with perfect-scrollbar, using [Perfect-Scrollbar](https://www.npmjs.com/package/perfect-scrollbar)

## Installation

```
npm install marko-perfect-scrollbar --save
```
or

```
yarn add marko-perfect-scrollbar
```

## Usage

```marko

<AutoScroll class="my-scroll"
            height="100%"
            style="padding:10px"
            noScrollX=true
            on-scroll-x("onScollX")/>

```
## Inputs Properties

Common properties you may want to specify include:

- `class` - apply a class to container
- `height` - apply directly a height value to container (px,%,...)
- `style` - apply a CSS style to container
- `scrollbarLength` - apply width or height to the scrollbar
- `noScollX` - disable horizontal scroll

For other properties, kindly refer to [Perfect-Scrollbar Documentation](https://www.npmjs.com/package/perfect-scrollbar)

## Events

- `on-scroll-x` - This event fires when the x-axis is scrolled in either direction.
- `on-scroll-left` - This event fires when scrolling to the left
- `on-scroll-right` - This event fires when scrolling to the right
- `on-reach-x-start` - This event fires when scrolling reaches the start of the x-axis
- `on-reach-x-end` - This event fires when scrolling reaches the end of the x-axis
- `on-scroll-y` - This event fires when the y-axis is scrolled in either direction
- `on-scroll-up` - This event fires when scrolling upwards
- `on-scroll-down` - This event fires when scrolling downwards
- `on-reach-y-start` - This event fires when scrolling reaches the start of the y-axis
- `on-reach-y-end` - This event fires when scrolling reaches the end of the y-axis (useful for infinite scroll)

Feedback & Contribution
-------

You know the say: No one is whole alone! So, feedbacks are all welcome. Kindly report any encounted [Issues here][] and I'll be glad to work on it right away. Thank you.


License
-------

This software is free to use under the MIT license. See the [LICENSE file][] for license text and copyright information.


[LICENSE file]: https://github.com/fabrice8/marko-intl-tel-input/blob/master/LICENSE
[Issues here]: https://github.com/fabrice8/marko-intl-tel-input/issues