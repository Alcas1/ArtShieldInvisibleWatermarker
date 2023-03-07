# Invisible Watermarker

#### For more details check out: https://artshield.io/blog/post/stable-diffusion-invisible-watermarker-the-math-and-our-algorithm-improvements

#### This is the code we're utilizing in https://artshield.io to apply our invisible watermark
As we have been moving very fast on this project, the code may not be the most clean, but hopefully this will provide some extra clarity and transparency

Don't have too much time, but I'll try to reorganize this in a more consumable format soon/package for everyone to use

#### We referenced this library for the algorithm: https://github.com/ShieldMnt/invisible-watermark
We've made slight changes to use the Pillow library instead of OpenCV2, and we compare if either saving as JPEG or PNG results in a successful watermarking.
