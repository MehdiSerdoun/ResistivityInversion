# ResistivityInversion
This github repository is associated to the paper named 'Inversion of resistivity properties through whole-rock geochemistry and IR spectroscopy using Machine-Learning', accepted in Geophysical Prospecting. 
This paper uses drillhole data collected for mineral exploration containing resistivity logs (ohm.m-1), whole-rock geochemistry with elemental concentrations in ppm and SWIR readings (350-2500nm). The goal of this study was to assess the potential use of geochemistry and IR spectroscopy to infer synthetic resistivity values, and hence synthetic resistivity logs that could be applied to zones in which resistivity logging was not historically performed for mineral exploration. 
Due to data privacy concerns, supporting data is not made available. However, this repository provides information about how data should be formatted for running the code appropriately. 

The code presented in this repository was designed to be run using a .csv or .xlsx file containing variables (geochemistry, resistivity and IR wavelengths) as columns and samples as rows. The code needs, for each sample, that each resistivity reading be associated to IR and geochemical data at the same point. In the study case presented in the paper, the three methods displayed very different sampling resolution (0.1m for downhole resistivity readings, 3m for IR spectra and up to 20m for geochemical composites). The choice was made to upscale IR and resistivity to geochemical sampling resolution using the arithmetic average. 

More details regarding the specific implementation of the method are provided along the code. 

The authors do not intend to maintain this code updated in the future.

The file gpr13627-sup-0001-SuppMat contains supporting information related to the published paper and contain all realizations of ML models whose results are presented in the article. It can be downloaded through this repository.
