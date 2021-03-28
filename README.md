This module will produce a biplot of the projected points in the space of 2D which correspond to the first two principal components and the direction of each variable in this space. You'll only need pandas, numpy, matplotlib and seaborn module loaded.


The transform method will give you a different result than the pca function in sklearn because sklearn just centralize, where here for the sake of the visualization the module will standarize the data.
