https://caniuse.com/#feat=css-mixblendmode
# CSS blend modes

- blend mode / background blend mode
  - need use polyfill
  - combine with filters (ex: blur)
  - blend mode can anyway combine each other
  - multiply, screen ....blahblah
  - difference
   > | A-B |
   
   combine with overlay/color

## Uniformnity
   una.im/CSSgram
   cssco.co
   colorfilter.css
## Simplicity
  > multiply
    use white color -> transparent

## Consistency
    Chrome / Safari work fine
    Firefox -> filter issue
    Edge -> x, not support color mode

   kazzkiq.github.com/svg-color-filter

## Bonus perf tips

   - start with your image
   - remove image contrast use like photoshop
   - reapply contrast use css filter
   ```
   filter: contrast
   ```

## Creativity
   - video + blend modes
   - visualization + blend modes
   - ecommerce + blend modes like change the cloth color for a shop website

> just because it's the norm, doesn't mean its the best solution.

## Conclusion
  Blend Modes because:
    - simplicity
    - uniformity
    - consistency
    - performance
    - creativity
    - empathy

