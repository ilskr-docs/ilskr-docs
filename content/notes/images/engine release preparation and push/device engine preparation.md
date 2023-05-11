Process to prepare engine release for devices (both: N2, Jetson). This process includes:
1. pc engine and results of this engine finalization and release (release name assigning, registration in the DB, all files renaming with release name, conservation)
2. device engine generation: 
- pc engine settings adaptation for work on device (main_params.yml file adaptation - params change)
- add extra files and scripts for device work to the engine pack 
- add exe for devices, create required for devices folders structure
- spy engine adding into device engine pack 
- store device releases pack + pc engine results on the local server in special place in client-breed-gender folders

3. push to git