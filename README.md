Analytics Engineering Project
STEP 1: Set-up GCP Infrastructure with Terraform. Kindly check the process via this link Cloud Set-up 
STEP 2: Kindly check out the data ingestion process into GCP(our Data Lake) and pipeline orchestration with Airflow via this link Data Ingestion.
STEP 3: We will now use Airflow to automate the creation of BigQuery(our Data Warehouse) tables, both normal and partitioned, from the files we stored in our Data Lake via this link  Data Warehouse
STEP 4: Transforming our data with DBT. The details of this step can be found here here .



STEP 5: Connect the transformed data to a visualization tool of your choice. In my case I used PowerBI



Using the starter project
Try running the following commands:
* dbt run
* dbt test
Resources:
* Learn more about dbt in the docs
* Check out Discourse for commonly asked questions and answers
* Join the dbt community to learn from other analytics engineers
* Find dbt events near you
* Check out the blog for the latest news on dbt's development and best practices



