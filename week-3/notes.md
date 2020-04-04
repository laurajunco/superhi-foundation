## Week 3

- Layout stuff into multiple columns
- **Hero** when the first section image takes uo the whole space of the screen

### Header and hero section html
- div tags are generic html elements used for structure
- In earlier html everything was divs

- Good range for body text is 14 to 20px


### floats
- Float property was designed  for having an image inside some text
- Text would wrap around said image
- When using float the elements get taken out of the regular flow of the page
- In doing that the parent element has no awareness of them being inside them.
- we need to force the header to recognize its inside floating elements
- Using overflow: hidden makes the parent container recognize its child floating elements size.
