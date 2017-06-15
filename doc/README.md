# Fragility in Networks Analysis
## By: Adam Li

# 1. Background

# 2. Methods
- Linear Time Varying Model
From EEG data, there will be a high dimensional channels X time recording data. We apply a sliding window with some overlap over the entire time series to create a model for each window of data. 

This achieves compression of the data into a series of matrices. The matrices will highlight the state evolution matrix from linear systems theory of a discrete time system. 

- Minimum Perturbation Computation
From each window, we compute the minimum norm perturbation matrix required to make the state evolution matrix to a specified radius, r. 

- Fragility Metric Computation


- ROC Curve Analysis


# 3. Future Directions


# 4. Code Usage
