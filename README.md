# marquee-line

## Installing

### Package manager

Using npm:

```bash
$ npm install marquee-line
```

Using yarn:

```bash
$ yarn add marquee-line
```

JS
```js
import marquee from 'marquee-line';

$('.marquee').marquee({
  mask: '.mask',
  line: '.line',
  animSpeed: 30,
  pauseOnHover: true,
});


Options

mask: null            // masking class which should have overflow hidden
line: '>*'            // line class which holds the crawling items
handleFlexible: true, // Boolean
pauseOnHover: true,   // Boolean
hoverClass: 'hover',  // hovere class
direction: 'left',    // left/right
cloneClass: 'cloned', // clone class
animSpeed: 10,        // px per second
initialDelay: 0       // milisecond
````

HTML
```html
<div class="marquee">
  <div class="mask">
    <div class="line">
      <div>Hello</div>
      <div>Hello</div>
      <div>Hello</div>
    </div>
  </div>
</div>
````
