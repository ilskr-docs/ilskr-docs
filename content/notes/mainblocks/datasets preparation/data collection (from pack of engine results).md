Collect the data from PC engine results

There's a strict system of datasets storaging in order to not mess datasets and always be able to find the exact dataset on which exact models were trained and errors were calculated. It's neccessary to be able always repeat previously got results. A unique name is also assigned to each new dataset and there're checks in order not to rewrite it. 

Storage on Moscow server: \\\Datasets\\chikens\\MHDR_Chicken\\sources\\datasets\\zbage_datasets
![[Pasted image 20230426173036.png]]

Inside each dataset folder also storaged: 
- snapshot of collect_dataset.py configs which were used during this particular dataset collection (collecting_params.yaml, test_filters.yaml, union_dataset.yaml)
- dataset check results 
- filtration results 
- log 
- csv datset file (collected_df.csv)

![[Pasted image 20230426173250.png]]


