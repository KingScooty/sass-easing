Awesome Sass Easing Variables
===========

# sass-easing
Some useful variables for easing animations using SASS. 
I'll add to this file whenever i come across a cool easing pattern.

## Install

```bash
$ npm install awesome-sass-easing --save
```

or

```
$ bower install sass-easing --save
```

## Usage

```SCSS
@import "../node_modules/awesome-sass-easing/_easings.scss";

.element {
  transition(top 500ms $easeInCubic);
}
```

##Easing Functions

The following easing functions are available:

- easeInSine
- easeOutSine
- easeInOutSine

- easeInQuad
- easeOutQuad
- easeInOutQuad

- easeInCubic
- easeOutCubic
- easeInOutCubic

- easeInQuart
- easeOutQuart
- easeInOutQuart

- easeInQuint
- easeOutQuint
- easeInOutQuint

- easeInExpo
- easeOutExpo
- easeInOutExpo

- easeInCirc
- easeOutCirc
- easeInOutCirc

- easeInBack
- easeOutBack
- easeInOutBack

- easeInOutFast

## License

MIT