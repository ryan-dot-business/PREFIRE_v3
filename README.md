# PREF*RE — homepage prototype

Static build of the new PREF*RE homepage and navigation, from the Figma file "PREF*RE — New Site" (frames *Home - Desktop*, *Home - Mobile*, *navigation*, and the G2 hero).

Open `index.html` in a browser. No build step or dependencies; fonts load from Google Fonts.

## What's in it

- **Nav**: HEAT (products + use cases) and Region dropdowns that share one surface with the bar; full-screen menu on mobile.
- **Hero slider**: Ultra, The Long Way, G2 x PREF*RE. Slides travel in the direction of the press (arrows, progress bars, swipe, ← →). Background, pouch, copy and button move as separate layers for parallax. Autoplay with pause.
- **Tiles**: Outdoor and Indoor, with scroll parallax on the hands shot.
- **Footer**.

## Notes

- All background gradients and dimming are baked into the images in `img/` (`-d` = desktop, `-m` = mobile crops). Only `transform` and `opacity` animate.
- Headlines use Archivo Condensed as a stand-in for Acumin Pro Condensed (Adobe Fonts); UI text uses the system font (SF Pro on Apple devices).
- "The Long Way" slide reuses the forest photo until its own image is ready.
- Links are placeholders (`#…`) and don't navigate.
