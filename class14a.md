# CSS Transforms, Transitions, and Animations Summary :

**Transform :**

The transform property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements.


* The scale value allows you to increase or decrease the size of an element.
>
* With the rotate value, the element rotates clockwise or counterclockwise by a specified number of degrees. A positive value, such as 90deg, rotates the element clockwise, while a negative value, such as -90deg, rotates it counterclockwise.
>
* The translate value moves an element left/right and up/down. The movement is based on the parameters given for the X (horizontal) Y (vertical) axes.
>
* With the skew value, the element skews (or tilts) one direction or the other based on the values given for the X and Y axes.


![](https://www.w3.org/TR/css-transforms-1/examples/svg-translate1.svg)


**Transitions :** 

*A shorthand property for setting the four transition properties into a single property.*

>

* **Transition-delay:** Specifies a delay (in seconds) for the transition effect.
>
* **Transition- duration:** Specifies how many seconds or milliseconds a transition effect takes to complete.
>
* **Transition-property:** Specifies the name of the CSS property the transition effect is for.
>
* **Transition-timing function:** Specifies the speed curve of the transition effect.


**Animations :**

***To use CSS animation, you must first specify some keyframes for the animation.
Keyframes hold what styles the element will have at certain times.***


* **The animation-iteration-count** property specifies the number of times an animation should run.
>
* **The animation-direction** property specifies whether an animation should be played forwards, backward, or in alternate cycles.
>
* **The animation-play-state** property allows an animation to be played or paused using the running and paused keyword values respectively.
>
* **The animation-fill-mode** property identifies how an element should be styled either before, after, or before and after the animation is run.


![ css animation ](https://stfalcon.com/uploads/images/5881e0b98e717.png)


[ the css animation Mdn](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)


