Statistics is file with historical mean value, stdev, filtration thresholds for such chicken features as: volume, max_axis, min_axis, height. This file is set in engine main_params.yaml file here: 

File is unique for each client-breed-gender and should be updated: 
1. When new combination client-breed-gender was registered and some data was collected - in process of first engine for this client-breed-gender calibration.
2. When big amount of new data for particular client-breed-gender was collected and statisics file is outdated (not appropriate mean or filtration threshold anymore

Example of part of statistics file for feature: volume_norm_corr 
![[Pasted image 20230417185411.png]]