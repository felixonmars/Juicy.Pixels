Juicy.Pixels
============

This library provide saving & loading of different picture formats for
the Haskell language. The aim of the library is to be as lightweight as
possible, you ask it to load an image, and it'l dump you a big MUArray 
or UArray full of juicy pixels. Or squared pixels, or whatever, as long
as they're unboxed.

Status
------

 - PNG    (.png) 
    * Reading : 1,2,4,8 bits loading, Grayscale, 24bits, 24 bits with alpha,
                interleaved & filtered (fully compliant with the standard,
                tested against png suite).
    * Writing : none yet.

 - Bitmap (.bmp) (mainly used as a debug output format)
    * Reading : none yet
    * Writing : 32bits (RGBA) per pixel images,

 - Jpeg   (.jpg, .jpeg) work in progress.

_I love juicy pixels_
