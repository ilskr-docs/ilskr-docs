-   Initialize config from config file
-   Load all metrics from PostgresDB for specified params:
    -   datasets of interest (usually full)
    -   metrics of interest (names from available SummaryGeneratorConfig.all_metrics)
    -   filters (only client|farm|breed_type|gender filters are available)
    -   filters (only client|farm|breed_type|gender filters are available)
    -   experiments keywords (check experiments and experiment_match_type in SummaryGeneratorConfig
-   For each filter will be created folder in global_reports_save_dir.
-   In each filter group folder will be created report file for each report_group_by_mode group , that will include all metrics for all clients|breed_type|gender
-   In each report will be created sheets with winners for specified by filters clients group and specified report_group_by_mode
-   Results on each filters group will also be printed in console like this

```jsx
CALC SCORES FOR CLIENT_1
GENERATING REPORT FOR dataset_20220930_union_train
WINNERS ORDER:
1 place: exp_cvec_s_wareog_reg_2 (10 wins)
2 place: exp_cvec_s_wareog_reg_5 (10 wins)
3 place: indi (9 wins)
4 place: exp_cvec_s_wareog_reg_4 (9 wins)
It meant that exp_cvec_s_wareog_reg_2 has the best metrics scores
```

 <font color="red"> Note: If only indi in winners order, then no results were found in dn for specified parameters</font>
 