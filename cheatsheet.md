# CSS Animation Cheatsheet

## `transition`

- `transition-property`
  - NOTE: The only values you should be specifying for this are `none`,
    `transform`, and `opacity`.
    - `transform` and `opacity` don't trigger reflow/layout, and they can be
      accelerated with the GPU
- `transition-duration`
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
  - useful for cleaning up event listeners
- `transitionrun`
- `transitioncancel`

## FLIP

- First Last Invert Play
