# 3D Image Sidebar

## Project overview

This repository contains a lightweight static webpage that demonstrates a 3D image sidebar UI effect. It's intended as a simple UI demo or starter template for galleries, portfolios, or UI experiments.

Built with:

- HTML (`index.html`) — markup and page structure
- CSS (`style.css`) — layout, 3D transforms and responsive styles
- JavaScript (`script.js`) — interactivity and sidebar behavior
- Assets/ — sample images used by the demo

## Short description (one-liner)

An interactive 3D-style image sidebar demo showing stacked images with hover and selection effects.



## Files in this project

- `index.html` — main page markup
- `style.css` — styles, layout and 3D transforms
- `script.js` — JS used to control sidebar interactions
- `Assets/` — sample images used by the demo (e.g. `Gojo.jpg`, `Sukuna.jpg`, etc.)

## How it works (high level)

- The sidebar uses CSS 3D transforms and transitions to create depth and layered stacking of images.
- `script.js` wires up hover or click handlers to animate images (bring forward, rotate slightly, or show details).
- Images live in the `Assets/` folder; the HTML references them by filename.

## Inputs / Outputs (contract)

- Inputs: image files placed in `Assets/` (common formats: jpg, jpeg, png). File names should match those referenced in `index.html`.
- Output: an interactive visual sidebar rendered in the browser.
- Error modes: missing images will show broken-image placeholders in the browser; if JavaScript fails the static layout still shows the images.

## Customization

- Replacing images: drop new images into `Assets/` and update `index.html` image `src` attributes.
- Change spacing/depth: edit `style.css` where the sidebar transforms and translateZ values are defined.
- Adjust interactivity: edit `script.js` to change event handlers (hover vs click), animation durations, or add keyboard controls.

## Accessibility

- Add meaningful `alt` text to the `<img>` elements in `index.html` if not already present.
- Consider adding keyboard focus styles and `tabindex` to interactive elements so keyboard users can navigate the sidebar.

## Browser support

Modern browsers with CSS 3D transform support (Chrome, Edge, Firefox, Safari) should render the effect correctly. Mobile behavior may differ — test on target devices.

## Development notes

- No build step required — this is a static site. Edit files directly and refresh the browser.
- Recommended: install a lightweight dev server (see "How to view") to avoid cross-origin restrictions when testing.

## Troubleshooting

- If images do not show, verify filenames in `index.html` and check `Assets/`.
- If animations are choppy, try reducing transition durations in `style.css` or test in a different browser.

## Suggestions / Next steps

- Add keyboard navigation and ARIA attributes for improved accessibility.
- Add a responsive layout that collapses the sidebar on small screens.
- Add captions and optional modal/lightbox view for each image.


## Credits

- Project created as a simple UI demo using plain HTML/CSS/JS.

---

If you want, I can also:

- Generate an accessible version with keyboard controls
- Convert the demo into a React/Vue component for reuse

## Preview 

- [3D Image Sidebar]( https://haseebjaved4212.github.io/3D-Image-SideBar/)
