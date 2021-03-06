## Image Link Slider

A simple image link slider component built for React. Uses react-router-dom for links, react-use-gesture for drag gesture scrolling, and react-spring for animation. Easily re-style to fit different use cases.

View it on github pages [here!](https://kadenceneuens.github.io/image-link-slider/)

### Usage
Where the slider is used, you can import a js array file with three fields: title, image, link

**title**: Shown on hover on bottom label\
**image**: Path to image to be displayed in this block\
**link**: Path to link when clicking through

then pass the file through props as 'data'

e.g.

```
import {items} from './ImageLinkSlider/SliderItems/Items"
...
return(
<>
  <ImageLinkSlider data={items}/>
</>
)
```

Default behaviour is to scale and center images to fill the slot.

### Dependencies
react-router-dom\
react-use-gesture\
react-spring v8
