# Analytics Engineering Project on NYC TaxiTrips Data

Dataset used in this project can be found here https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

STEP 1: Set-up GCP Infrastructure with Terraform. Kindly check the process via [cloud set-up](https://github.com/ziritrion/dataeng-zoomcamp/blob/main/notes/1_intro.md#terraform-and-google-cloud-platform).


STEP 2: Kindly check out the data ingestion process into GCP(our Data Lake) and pipeline orchestration with Airflow via [Ingestion](https://github.com/ziritrion/dataeng-zoomcamp/blob/main/notes/2_data_ingestion.md#orchestration-with-airflow)


STEP 3: We will now use Airflow to automate the creation of BigQuery(our Data Warehouse) tables, both normal and partitioned, from the files we stored in our Data Lake via [Warehouse](https://github.com/ziritrion/dataeng-zoomcamp/blob/main/notes/3_data_warehouse.md#bigquery)


STEP 4: Transforming our data with DBT. The details of this step can be found [Here](https://github.com/ziritrion/dataeng-zoomcamp/blob/main/notes/4_analytics.md#introduction-to-analytics-engineering)

![image](https://user-images.githubusercontent.com/64735216/192162170-8971ad63-e8b8-4f81-a975-4beb6e732247.png)

STEP 5: Connect the transformed data to a visualization tool of your choice. In my case I used PowerBI and below is a sample visualization.

![image](https://user-images.githubusercontent.com/64735216/192162131-45a8965f-8c71-4a8b-8e73-3c0fc19d25b9.png)
