# rainbowjs
A simple JS class to add a rainbow outline

![image](https://github.com/user-attachments/assets/16a62abc-902d-4682-8f89-9c68dc453afa)


# Usage

```js
import { RainbowText } from "./rainbow.js";

document.addEventListener("DOMContentLoaded", () => {
  const rainbowTitle = new RainbowText()
  // add the id of the object to add the effect on
  rainbowTitle.rainbow("prjTitle")

  // alternatively supply custom colors
  //rainbowTitle.rainbow("prjTitle",customHighlightColors)

  // can also be applied onto an existing class
  //rainbowTitle.rainbow("prjTitle",customHighlightColors, "classNameHere")
});


const customHighlightColors = {
  1: '#FFB5E8',  // Soft pink
  2: '#B28DFF',  // Lavender
  3: '#BFFCC6',  // Mint
  4: '#FFC9DE',  // Salmon pink
  default: '#C5A3FF'  // Light purple
}
```
