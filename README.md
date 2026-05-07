# ElectronPrecip_Conjunction_MLT
A set of 5 conjunction-trained artificial neural network (ANN) that requires low-Earth-orbit electron fluxes, L and MLT, Lat and Lon, MLat and MLon, and AE measurements as sole inputs

# Python Dependencies
1. Python >= 3.11.7
2. numpy >= 1.24.3
3. matplotlib >= 3.8.0
4. scikit-learn >= 1.3.0
5. pandas >= 2.1.4
6. notebook >=7.0.6
7. scipy >=1.11.0

# Data
1. The RBSP A/B MagEIS ‘release 4 (rel04)’ level 3 data are publicly accessible at https://cdaweb.gsfc.nasa.gov/pub/data/rbsp/rbspa/l3/ect/mageis/sectors/rel04/ and https://cdaweb.gsfc.nasa.gov/pub/data/rbsp/rbspb/l3/ect/mageis/sectors/rel04/.
2. The POES MetOp/NOAA data are publicly accessible at https://www.ncei.noaa.gov/data/poes-metop-space-environment-monitor/access/l1b/v01r00/.
3. The OMNI data are publicly accessible at https://cdaweb.gsfc.nasa.gov/pub/data/omni/omni_cdaweb/.
4. For the input files (matfile_SP##.mat and SP##_May2017Feb2018.mat) visit https://doi.org/10.5281/zenodo.20076020

# Code Structure
Files: EPML_SP##.ipynb for METOP1, METOP2, NOAA15, NOAA18, NOAA19

1. Create and format a data frame (from matfile_SP##.mat)
2. Establish train and test data
3. Train MLPRegressor ANN
5. May 2017 to Mar 2018 Testing (using SP##_May2017Feb2018.mat)

# Correspondence
Dominique Stumbaugh (PhD student), University of California, Los Angeles. dstumbaugh@ucla.edu
