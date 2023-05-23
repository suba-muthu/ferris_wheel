## About the project

* It is a basic html and css animation project.

## Tools used

* HTML
* CSS

## About the project

* transform-origin - allows you to change the position of transformed elements.
    * syntax - transform-origin: x-axis y-axis z-axis|initial|inherit;
* transform property - allows you to manipulate the shape of an element.
    * transform: rotate(60deg);
    * rotate(60deg) - rotate the element around its transform-origin point by 60 degrees clockwise.
* @keyframes - The @keyframes rule specifies the animation code. It is used to define the flow of a CSS animation.
    * syntax - @keyframes animationname {keyframes-selector {css-styles;}}
    * Specify when the style change will happen in percent, or with the keywords "from" and "to", which is the same as 0% and 100%. 0% is the beginning of the animation, 100% is when the animation is complete.
* animation-name - specifies a name for the @keyframes animation. It is used to link a @keyframes rule to a CSS selector.
* animation-duration - defines how long an animation should take to complete one cycle.
    * syntax - animation-duration: time.
    * The time should be specified in either seconds (s) or milliseconds (ms).
* animation-iteration-count - This property sets how many times your animation should repeat.
    * syntax - animation-iteration-count: number.
    * This can be set to a number, or to infinite to indefinitely repeat the animation.
* animation property - It is a shorthand property.
    * syntax - animation: name duration timing-function delay iteration-count direction fill-mode play-state;
* animation-timing-function - specifies the speed curve of an animation.
    * animation-timing-function: ease-in-out;
    * ease-in-out - animation to start and end at a slower pace, but move more quickly in the middle of the cycle.

## Production Link

https://ferris-wheel-woad.vercel.app/