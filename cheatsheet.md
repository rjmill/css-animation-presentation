# CSS Animation Cheatsheet

## Realtime vs non-realtime animations

- 


## `transition`

- `transition-property` The CSS property you want to animate on transition
  - NOTE: The only values you should be specifying for this are `none`,
    `transform`, and `opacity`.
    - `transform` and `opacity` don't trigger reflow/layout, and they can be
      accelerated with the GPU
- `transition-duration` How long you want the transition to last
- `transition-timing-function` 
- `transition-delay`


Example
```
.some-identifier {
  transition-property: opacity;
  transition-duration: 100ms;
  transition-timing-function: ease-in-out;
  transition-delay: 1s;
}
```

### JavaScript events

- `transitionend`
- `transitionrun`
- `transitioncancel`
