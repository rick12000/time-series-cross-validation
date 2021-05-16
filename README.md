The package provides quick train/test split indexing for cross validation, specifically optimized for time series data.
There are two primary output options:
1. Expanding Window - in which the training window becomes larger with each fold and is always overlapping with part of the previous.
2. Rolling Window - in which the training window is of a fixed pre specified dimension, and it may or may not overlap depending on the rolling step specified.