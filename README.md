# hipps
Hygracose-based Irregular Packing Problem Solver

This repository contains files mentioned in my [Master Thesis on Constrained graph search-based polygon packing](http://longnguyenhuu.com/portfolio-item/2d-polygon-packing-program/). It was meant to contain the application code of my packing application *ippy*, using the [hygracose repository](https://github.com/hsandt/hygracose) as submodule, where hygracose would contain generic code for graph-constrained search (unrelated to polygon packing).

I didn't have time to split the two in the end, so I will instead redirect you the Bitbucket repository containing all the application's code: [ippy repository on BitBucket](https://bitbucket.org/hsandt/ippy)

The generic search code I was supposed to extract into hygracose is broadly what can be found in ippy/search/constraint.py, but I don't guarantee that it is isolated enough to work on its own, nor that it is sufficient to actually do proper graph search.