AstroDroid
==========
 DIY telescope
 dobsonian
 motorized
 guide scope for automatic pointing. use database of brightest starts
 plate solver to determine where guide scope is poiting
 use open cv to determine optical flow and learn how to control telescope. neural network unsupervised learning
 i.e. point the telescope somewhere, it uses plate solving to determinw where its pointing. it should also know its alt / az co-ordinates
 needs to know how to move the motors to keep pointed at the exact same point. should be independent of telescope set up...it should leaen and improve over time
 may need to ensure the base is perfectly level and pointing north for instance to get reproducible results but the NN may be able to handle slight deviations in setup and constructio accuracy etc. in any case
 problem....field derotation. maybe for guiding this is not needed since the software can handle it. but for main scope need to do it if we want long exposures.
