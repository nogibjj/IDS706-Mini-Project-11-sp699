# IDS-706-Data-Engineering :computer:

## Mini Project 11 :page_facing_up: 

## :ballot_box_with_check: Requirements
* Create a data pipeline using Databricks.</br>
* Include at least one data source and one data sink.</br>

## :ballot_box_with_check: To-do List
* __Pipeline functionality__: Learn how to build the data pipeline and its functioniality.</br>
* __Data source and sink configuration__: Perfectly configure the data source and sink.

## :ballot_box_with_check: Dataset
`BaskinRobbins.csv`
  ![image](https://github.com/suim-park/Mini-Project-11/assets/143478016/2fc283f8-e1ef-4997-9d2e-8d6daeb70196) </br>
  - The data includes information about the flavors at Baskin-Robbins and their nutritional content.
  - [BaskinRobbins.csv](https://github.com/nogibjj/IDS706-Mini-Project-11-sp699/blob/main/BaskinRobbins.csv)

## :ballot_box_with_check: Main Progress
#### `Section 1` Ingest the Raw Data
##### Load the raw data into a table to make it available for further processing.
* Load the raw data from the CSV file and create a table for usage.
![image](https://github.com/suim-park/Mini-Project-11/assets/143478016/b87f9aed-6b1d-4b20-ac79-32e3518d4773)

#### `Section 2` Prepare the Raw Data
##### Transform the raw BaskinRobbins data by adding a new column that contains only the fat grams, excluding trans fat.
* The prepared dataset includes the new column, 'Fat without Trans (g)'
  ![image](https://github.com/suim-park/Mini-Project-11/assets/143478016/02e06469-dece-4a8c-ae8a-3687fac90cad) </br>
  
