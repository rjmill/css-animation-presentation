# points

- transitions vs animations
- hardware acceleration
- reflow/layout
- what should animations be used for?
  - aren't they kind of cheesy?
  - object permanence
  - humans are super visual
- request animation frame
- web animation API
  - [polyfill](https://github.com/web-animations/web-animations-js)

## transition
The transition CSS property is a shorthand property for transition-property,
transition-duration, transition-timing-function, and transition-delay.


Transitions enable you to define the transition between two states of an
element. Different states may be defined using pseudo-classes like :hover or
:active or dynamically set using JavaScript.

[source](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)


# Quotes
> Conceptual models are valuable in providing understanding, in predicting how
> things will behave, and in figuring out what to do when things do not go as
> planned
- Don Norman
- The Design of Everyday Things
- p.28

> More of the brain is devoted to vision and visual processing than any other
> known function, including language. More neurons in the human brain are
> involved in vision than is the case of all the other sensory modalities
> combined.
- Dr. Leo Chalupa
- Show & Tell (Dan Roam)
  - p.178

# Sources
- transition
  - https://developer.mozilla.org/en-US/docs/Web/CSS/transition
  - https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions
- FLIP
  - https://css-tricks.com/animating-layouts-with-the-flip-technique/
  - https://aerotwist.com/blog/flip-your-animations/
- ux
  - https://medium.com/ux-in-motion/creating-usability-with-motion-the-ux-in-motion-manifesto-a87a4584ddc
- easing
  - https://easings.net/
- css pseudo-classes
  - https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes

- requestAnimationFrame
  - https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame

- transform
  - https://developer.mozilla.org/en-US/docs/Web/CSS/transform

- animation
  - https://developer.mozilla.org/en-US/docs/Web/CSS/animation


# questions

- [ ] why do we need two requestAnimationFrame calls to keep from applying the
  transition class on the first transformation?
