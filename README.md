# Push Loader

A progress indicator where a stick figure pushes the word **LOADING**. The letters get squeezed together from the right, and the screen shifts from green-black to orange as the pressure builds. At 100% the word springs open into **COMPLETE!**, the figure is thrown out of frame, and the palette turns green.

**Live demo:** https://dakotashao.github.io/push-loader/

You can also open `index.html` directly in a browser. It is one self-contained file: the BenchNine font is embedded and there are no dependencies.

## Modes

Switch between the two modes with the labels at the bottom of the page.

- **Determinate**: the squeeze follows progress from 0 to 100%. It plays through on its own and loops.
- **Indeterminate**: the figure pushes, then takes a break in one of several ways: getting shoved back, leaning its back against the word, doubling over to catch its breath, wiping its brow, or backing up for a run-up. Click anywhere to trigger completion.

## Palette

| State | Background | Foreground |
|---|---|---|
| Loading | `#071C03` | `#E2E9DC` |
| Squeezed | `#EB4626` | `#FAE7CE` |
| Complete | `#071C03` | `#98E260` |
