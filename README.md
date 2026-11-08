# adam-fun-pages

## The Bowl Index

An interactive 3D field guide to how much fits in a bowl, built with Three.js and GSAP.

Published URL: https://adambombtastic.github.io/adam-fun-pages/

### Publish on GitHub Pages

In Settings → Pages, select **Deploy from a branch**, choose **main** and **/ (root)**, then save. GitHub Pages publishes updates when changes are pushed to main.

### Run locally

```sh
python3 -m http.server 8080
```

Open http://localhost:8080. Internet access is required for Three.js, GSAP, and Google Fonts.

Counts are illustrative volume-based estimates, not physical packing measurements.

## Play with the bowl

- Explore 20 items through the story picker or **20 things** collection.
- Switch between **Top view** and **Side view** at any time.
- Enter **Play sandbox** to mix individual items. Add one, add five, or make a surprise mix. Tap an object to select it, or use the object picker, then remove it. **Empty bowl** starts again.
- Sandbox renders at most 150 individual objects for responsiveness. It is an illustrative arrangement, not a physics simulation. Changing bowl size clears the sandbox.
- Desktop controls sit beside the bowl; phone controls use a scrollable bottom tray. Reduced-motion preferences disable falling and decorative motion.

Responsive design follows [Impeccable adapt](https://github.com/pbakaus/impeccable/blob/main/skill/reference/adapt.md): touch targets, safe areas, progressive disclosure, and layouts adapted to portrait and landscape.
