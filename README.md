Some basic implementations of a few perlin noise algorithms in JavaScript using
[Phaser.js](http://phaser.io/).

original.html contains the original algorithm.

improved.html contains the improved algorithm based on the implementation
presented at [SIGGRAPH 2002](http://mrl.nyu.edu/~perlin/noise/).

simplex.html contains some experiments with simplex noise which is often used
to mimic Perlin noise. In theory it's faster to generate, but my
implementation seems slower. I prefer the noise generated from the other
algorithms, so I haven't developed this further, but I'm sure it could get
faster with a bit of work.

I am endebted to gdcbyers for [Noisy](http://mrl.nyu.edu/~perlin/noise/) and
Adrian Biagioli for [this excellent blog post](http://flafla2.github.io/2014/08/09/perlinnoise.html)
that helped me piece all this together.

Feel free to do anything you like with this code, I hope it helps!
