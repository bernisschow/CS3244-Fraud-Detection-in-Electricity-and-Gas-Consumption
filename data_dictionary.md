# Data Dictionary 

## Overview
This data dictionary describes the datasets used in this project for our model development process, including their purpose, data types, and any relevant details.

## Dataset: final_dataset.csv / train_set.csv / test_set.csv
- **Description**: This dataset comprises of cleaned and aggregated client data in the Tunisian Company of Electricity and Gas (STEG). The transformations were made after conducting exploratory data anlysis on the raw data.
- **Source**: https://www.kaggle.com/datasets/mrmorj/fraud-detection-in-electricity-and-gas-consumption (raw data). You may refer to our data_cleaning_and_EDA.ipynb and resampling.ipynb script to look at the transformations.
- **Last Updated**: Unknown (Raw data)

| Column Name                             | Data Type | Description                                                                                                                     |
|-----------------------------------------|-----------|---------------------------------------------------------------------------------------------------------------------------------|
| **client_id**                           | `object`  | Unique identifier for each client.                                                                                              |
| **creation_date**                       | `object`  | Date at which client account was created.                                                                                       |
| **fraud_status**                        | `float64` | Target variable on whether client is fraudulent or not.                                                                         |
| **creation_year**                       | `int64`   | Year at which client account was created.                                                                                       |
| **creation_month**                      | `int64`   | Month at which client account was created.                                                                                      |
| **creation_day**                        | `int64`   | Day at which client account was created.                                                                                        |
| **region_101**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 101.                                                          |
| **region_103**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 103.                                                          |
| **region_104**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 104.                                                          |
| **region_105**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 105.                                                          |
| **region_106**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 106.                                                          |
| **region_107**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 107.                                                          |
| **region_199**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 199.                                                          |
| **region_206**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 206.                                                          |
| **region_301**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 301.                                                          |
| **region_302**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 302.                                                          |
| **region_303**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 303.                                                          |
| **region_304**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 304.                                                          |
| **region_305**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 305.                                                          |
| **region_306**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 306.                                                          |
| **region_307**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 307.                                                          |
| **region_308**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 308.                                                          |
| **region_309**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 309.                                                          |
| **region_310**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 310.                                                          |
| **region_311**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 311.                                                          |
| **region_312**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 312.                                                          |
| **region_313**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 313.                                                          |
| **region_371**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 371.                                                          |
| **region_372**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 372.                                                          |
| **region_379**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 379.                                                          |
| **region_399**                          | `int64`   | One-hot encoded variable to indicate if the client is from region 399.                                                          |
| **district_62**                         | `int64`   | One-hot encoded variable to indicate if the client is from district 62.                                                         |
| **district_63**                         | `int64`   | One-hot encoded variable to indicate if the client is from district 63.                                                         |
| **district_69**                         | `int64`   | One-hot encoded variable to indicate if the client is from district 69.                                                         |
| **client_catg_11**                      | `int64`   | One-hot encoded variable to indicate if the client is categorised as client type 11.                                            |
| **client_catg_12**                      | `int64`   | One-hot encoded variable to indicate if the client is categorised as client type 12.                                            |
| **client_catg_51**                      | `int64`   | One-hot encoded variable to indicate if the client is categorised as client type 51.                                            |
| **consumption_level_1_mean**            | `float64` | Mean consumption of meter level 1 for each client.                                                                              |
| **consumption_level_1_std**             | `float64` | Standard Deviation of consumption of meter level 1 for each client.                                                             |
| **consumption_level_1_min**             | `float64` | Minimum consumption value of meter level 1 for each client.                                                                     |
| **consumption_level_1_max**             | `float64` | Maximum consumption value of meter level 1 for each client.                                                                     |
| **consumption_level_1_sum**             | `float64` | Sum of total consumption value of meter level 1 for each client.                                                                |
| **consumption_level_2_mean**            | `float64` | Mean consumption of meter level 2 for each client.                                                                              |
| **consumption_level_2_std**             | `float64` | Standard Deviation of consumption of meter level 2 for each client.                                                             |
| **consumption_level_2_min**             | `float64` | Minimum consumption value of meter level 2 for each client.                                                                     |
| **consumption_level_2_max**             | `float64` | Maximum consumption value of meter level 2 for each client.                                                                     |
| **consumption_level_2_median**          | `float64` | Median consumption value of meter level 2 for each client.                                                                      |
| **consumption_level_2_sum**             | `float64` | Sum of total consumption value of meter level 2 for each client.                                                                |
| **consumption_level_3_mean**            | `float64` | Mean consumption of meter level 3 for each client.                                                                              |
| **consumption_level_3_min**             | `float64` | Minimum consumption value of meter level 3 for each client.                                                                     |
| **consumption_level_3_max**             | `float64` | Maximum consumption value of meter level 3 for each client.                                                                     |
| **consumption_level_3_sum**             | `float64` | Sum of total consumption value of meter level 3 for each client.                                                                |
| **consumption_level_4_mean**            | `float64` | Mean consumption of meter level 4 for each client.                                                                              |
| **consumption_level_4_min**             | `float64` | Minimum consumption value of meter level 4 for each client.                                                                     |
| **consumption_level_4_max**             | `float64` | Maximum consumption value of meter level 4 for each client.                                                                     |
| **consumption_level_4_median**          | `float64` | Median consumption value of meter level 4 for each client.                                                                      |
| **consumption_level_4_sum**             | `float64` | Sum of total consumption value of meter level 4 for each client.                                                                |
| **old_index_mean**                      | `float64` | Mean old meter index for each client.                                                                                           |
| **old_index_min**                       | `float64` | Minimum old meter index for each client.                                                                                        |
| **old_index_max**                       | `float64` | Maximum old meter index for each client.                                                                                        |
| **old_index_median**                    | `float64` | Median value of old meter index for each client.                                                                                |
| **diff_in_index_mean**                  | `float64` | Mean difference in meter index for each client.                                                                                 |
| **diff_in_index_std**                   | `float64` | Standard Devation difference in meter index for each client.                                                                    |
| **diff_in_index_min**                   | `float64` | Minimum difference in meter index for each client.                                                                              |
| **diff_in_index_max**                   | `float64` | Maximum difference in meter index for each client.                                                                              |
| **diff_in_index_sum**                   | `float64` | Sum of difference in meter index for each client.                                                                               |
| **total_consumption_mean**              | `float64` | Mean total consumption across all meter levels 1, 2, 3 and 4 for each client.                                                   |
| **total_consumption_std**               | `float64` | Standard Deviation total consumption across all meter levels 1, 2, 3 and 4 for each client.                                     |
| **total_consumption_min**               | `float64` | Minimum total consumption across all meter levels 1, 2, 3 and 4 for each client.                                                |
| **total_consumption_max**               | `float64` | Maximum total consumption across all meter levels 1, 2, 3 and 4 for each client.                                                |
| **total_consumption_sum**               | `float64` | Sum of total consumption across all meter levels 1, 2, 3 and 4 for each client.                                                 |
| **months_number_min**                   | `float64` | Minimum value of months_number for each client.                                                                                 |
| **months_number_max**                   | `float64` | Maximum value of months_number for each client.                                                                                 |
| **months_number_median**                | `float64` | Median value of months_number for each client.                                                                                  |
| **meter_number_count**                  | `float64` | Total no. of unique meter_number values that is tied to each client across their invoices.                                      |
| **meter_code_count**                    | `float64` | Total no. of unique meter_code values that is tied to each client across their invoices.                                        |
| **no_of_invoices**                      | `float64` | Total no. of invoices that each client has had been billed.                                                                     |
| **time_since_last_invoice_mean**        | `float64` | Mean time passed in days since the previous invoice per client.                                                                 |
| **time_since_last_invoice_std**         | `float64` | Standard deviation of time passed in days since the previous invoice per client.                                                |
| **time_since_last_invoice_min**         | `float64` | Minimum time passed in days since the previous invoice per client.                                                              |
| **time_since_last_invoice_max**         | `float64` | Maximum time passed in days since the previous invoice per client.                                                              |
| **time_since_last_invoice_median**      | `float64` | Median time passed in days since the previous invoice per client.                                                               |
| **meter_status_1.0**                    | `float64` | No. of invoices of each client receiving meter_status of category 1 across all their invoices.                                  |
| **meter_status_2.0**                    | `float64` | No. of invoices of each client receiving meter_status of category 2 across all their invoices.                                  |
| **meter_status_3.0**                    | `float64` | No. of invoices of each client receiving meter_status of category 3 across all their invoices.                                  |
| **meter_status_4.0**                    | `float64` | No. of invoices of each client receiving meter_status of category 4 across all their invoices.                                  |
| **meter_coefficient_0**                 | `float64` | No. of invoices of each client receiving meter_coefficient value of 0 across all their invoices.                                |
| **meter_coefficient_2**                 | `float64` | No. of invoices of each client receiving meter_coefficient value of 2 across all their invoices.                                |
| **meter_coefficient_3**                 | `float64` | No. of invoices of each client receiving meter_coefficient value of 3 across all their invoices.                                |
| **meter_coefficient_4**                 | `float64` | No. of invoices of each client receiving meter_coefficient value of 4 across all their invoices.                                |
| **meter_coefficient_10**                | `float64` | No. of invoices of each client receiving meter_coefficient value of 10 across all their invoices.                               |
| **meter_coefficient_11**                | `float64` | No. of invoices of each client receiving meter_coefficient value of 11 across all their invoices.                               |
| **meter_coefficient_20**                | `float64` | No. of invoices of each client receiving meter_coefficient value of 20 across all their invoices.                               |
| **meter_coefficient_30**                | `float64` | No. of invoices of each client receiving meter_coefficient value of 30 across all their invoices.                               |
| **meter_coefficient_33**                | `float64` | No. of invoices of each client receiving meter_coefficient value of 33 across all their invoices.                               |
| **meter_coefficient_40**                | `float64` | No. of invoices of each client receiving meter_coefficient value of 40 across all their invoices.                               |
| **meter_coefficient_50**                | `float64` | No. of invoices of each client receiving meter_coefficient value of 50 across all their invoices.                               |
| **reading_remark_6**                    | `float64` | No. of invoices of each client receiving note category 6 from STEG agent across all their invoices.                             |
| **reading_remark_7**                    | `float64` | No. of invoices of each client receiving note category 7 from STEG agent across all their invoices.                             |
| **reading_remark_8**                    | `float64` | No. of invoices of each client receiving note category 8 from STEG agent across all their invoices.                             |
| **reading_remark_9**                    | `float64` | No. of invoices of each client receiving note category 9 from STEG agent across all their invoices.                             |
| **meter_type_0**                        | `float64` | No. of invoices of each client for electricity (coded as 0) meter.                                                              |
| **meter_type_1**                        | `float64` | No. of invoices of each client for gas (coded as 1) meter.                                                                      |
| **is_index_discrepancy_False**          | `float64` | No. of invoices of each client where total consumption is not reflected accurately in their change of meter index across all their invoices.    |
| **is_index_discrepancy_True**           | `float64` | No. of invoices of each client where total consumption is reflected accurately in their change of meter index across all their invoices.        |
