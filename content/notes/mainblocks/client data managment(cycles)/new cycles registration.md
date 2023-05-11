Cycle houses are registered in semi-automatic mode: 
1. auto scanning of AWS/GoogleDrive, 
2. getting data for found new cycle-houses from Mongo (breed, gender, cycle_start_day)
3. manual check of data (need to assign short name of farm - if that's new farm, need to assign Cycle common name for houses from one client which started in the same time and we consider it as one cycle)
4. Update database with manually checked final client data