This repository contains spectra, response files, and other miscellaneous analysis for the XRISM observation 201064010; mostly oriented towards building an observing proposal for GO Cycle 3.

the /analysis/ folder contains spectra and *basic* response files for both the full observation, and three distinct time bins.
These data were reprocessed using XRISM CalDB 12. I only took a cursory glance at the branching ratios to ensure nothing was wildly abnormal, and as such only pixel 12 is excluded, and no time filtering was done (beyond the bins for analysis purposes). Response files are fairly minimal: "Small" RMFs are included, which *only* describes a Gaussian core. The following response behavior are not modeled: exponential tail, Si K$\alpha$ instrument line, escape peak, and electron loss continuum.

Time intervals filtered as Bins I, II, and III are shown in the image below:
![Time bins](https://github.com/colinbourque/xa201064010/blob/main/lightcurve/bins.png "Time bins")
