![Data Pipeline](https://github.com/nogibjj/IDS706-Mini-Project-11-sp699/actions/workflows/cicd.yml/badge.svg)
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
#### `Section 1` Create a Cluster
##### Create a cluster to provide the compute resources needed to run commands.

#### `Section 2` Explore the Source Dta
##### To learn how to use the Databricks interface to explore the raw source data, see Explore the source data for a data pipeline.

#### `Section 3` Ingest the Raw Data
##### Load the raw data into a table to make it available for further processing.
* Load the raw data from the CSV file and create a table for usage.

![image](https://github.com/suim-park/Mini-Project-11/assets/143478016/b87f9aed-6b1d-4b20-ac79-32e3518d4773)

#### `Section 4` Prepare the Raw Data
##### Transform the raw BaskinRobbins data by adding a new column that contains only the fat grams, excluding trans fat.
* The prepared dataset now includes an additional column named 'Fat without Trans (g)'.

  ![image](https://github.com/suim-park/Mini-Project-11/assets/143478016/02e06469-dece-4a8c-ae8a-3687fac90cad) </br>
  ![image](https://github.com/nogibjj/IDS706-Mini-Project-11-sp699/assets/143478016/27302932-fdd1-4f7b-8d57-b6346fbd848c) </br>
  ![image](https://github.com/nogibjj/IDS706-Mini-Project-11-sp699/assets/143478016/84e31ed2-8dc2-4683-8ccd-21f20ee9e5e5)

#### `Section 5` Query the Transformed Data
##### Extend the processing pipeline by adding queries to analyze the Baskin Robbins data. This query uses the prepared data created in the previous step.
* The query creates a new table that categorizes the 'Fat without Trans' amount as low, medium, or high.

![image](https://github.com/nogibjj/IDS706-Mini-Project-11-sp699/assets/143478016/4dd6eb7d-0bd7-435f-b1db-6b1882d0ccb7) </br>
* When you run the query, the new dataset has showed up.

![image](https://github.com/nogibjj/IDS706-Mini-Project-11-sp699/assets/143478016/e09cd9a2-1566-4294-8de3-fa45d977de50) </br>
![image](https://github.com/nogibjj/IDS706-Mini-Project-11-sp699/assets/143478016/31233e21-8334-4298-8712-2051e292a443)

#### `Section 6` Create a Databricks Job to Run the Pipeline
##### Create a workflow to automate running the data ingestion, processing, and analysis steps using a Databricks job.
* The job will be executed according to a designated schedule.

![image](https://github.com/nogibjj/IDS706-Mini-Project-11-sp699/assets/143478016/4cd05475-9796-49c1-a8de-879f1adaf3dc) </br>

#### `Section 7` Schedule the Data Pipeline Job
##### Define a schedule for the job that runs the pipeline.
* The job is scheduled to run at the same time every instance.
![image](https://github.com/nogibjj/IDS706-Mini-Project-11-sp699/assets/143478016/e7ad3f34-2185-4f52-a743-662b7d8d372c)
