# fiziko

This MetaPost package, initially developed to facilitate preparing a body of illustrations for a physics textbook, includes a set of "low level" macros, required for aesthetically pleasing appearance of black and white illustrations, as well as "higher level" ones, that rely on them.

The idea behind the package is that resolution of printing is often insufficient to make ugly raster halftone patterns invisible, and even when resolution is sufficient, generic digital gradient shading looks plasticky and boring, so, one possible solution is, instead of relying on ordinary halftones, to mock woodcut or ink drawing shading with reasonably thin strokes that will give some oldschool feel to illustrations. By changing minimal stroke width it is possible to quickly adjust illustrations to be printed with given hardware limitations without or with minimal changes in illustrations themselves. 

In order to make illustrations look less mechanically monotonous, as digital illustrations often do, some degree of randomness is introduced here and there.

Apart from macros related to these aesthetical complications, "fiziko" package contains several macros of general interest that were used in abovementioned textbook.
