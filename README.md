# RGB Display Rendering Transform (rgbDRT)

A minimal per-channel display transform.
- Uses the ["Michaelis-Menten Spring Dual Contrast" tonescale](https://colab.research.google.com/drive/10C3HvDuoAhYad1qOG2r0v8fGR-5VdpO5) curve.
- Uses a custom set of rendering primaries, tuned by hand for pleasing hue and chroma rendering.
- If you don't like it, you can make your own. I've included the setup I used in the [utils](/utils) folder.

