# Dataset

The dataset (too large to be hosted on github) is available [here](https://drive.google.com/file/d/19cZezWLLXWDxGrw9By6uTRSidMENrAew/view?usp=sharing)

It is one of the operational simulations of the LSST that was released to accompany a whitepaper call for the LSST observing strategy (which is what I work on). 

I have turned it into a csv file to be easily used with a pandas df.

It includes the following columns:

| Column         |      Description      
|----------------|--------------
| night          |  night observation was taken on 
| filter         |  one of 'ugrizy'
| proposalId     |  WFD (wide-fast-deep) main survey is 3, other numbers for the minisurveys
| fieldRA        | right ascension of center of observation
| fieldDec       | decliation of center of observation
| fiveSigmaDepth | depth (magnitude) of observation
| slewTime       | time it took the telescope to slew to the position
| moonAlt        | altitude of moon
| moonRA         | right ascension of moon
| moonDec        | declination of moon
| airmass        | value of airmass
| skyBrightness  | value of sky brightness
| seeingFwhmGeom | seeing (goodness of observing conditions)
