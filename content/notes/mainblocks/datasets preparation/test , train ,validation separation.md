Test and train splitting can be random or manually set. 
To set it manual - it's neccessary to specify what exact cycle-houses for each client/breed/gender should be used as test and remain - for train and validation. Validation is always allocated automatically. 

Example of test_filters.yaml config where all houses which should used as test are specified.

![[Pasted image 20230426174127.png]]

Train, test and full (train+test) datasets are stored separately and have common name: 
![[Pasted image 20230426175004.png]]