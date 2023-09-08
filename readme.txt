This is a bug fixed version of original PNGImage 1.564.

1. Remove canvas support because it raises exception while destroying sometimes.
2. Enhance assign procedures to keep color palette.
3. Fix memory accessing violation in zlib compressing and decompressing code while loading or saving some pictures.

* only tested with Delphi 7.
