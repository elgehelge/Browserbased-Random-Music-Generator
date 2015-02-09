Thanks to:
* https://gist.github.com/Likeyn/824f5b3e9278fa0c8745
* https://github.com/possan/wavepot-runtime
* sylvester.js

Right now a composition is based on:
* bmp (60-180)
* scale (out of around 20 predefined ones)
* 4 chords:
  * octave (-1, 0 or 1)
  * 3 nodes (0-12)
* baseline:
  * 4 nodes from octave 0 (0-12)
* step sequencer:
  * 5x16 matrix with values between 0 and 1
  * 5x8 matrix with values between 0 and 1 (this is repeated 2 times)
  * 5x4 matrix with values between 0 and 1 (this is repeated 4 times)
  * 5x2 matrix with values between 0 and 1 (this is repeated 8 times)