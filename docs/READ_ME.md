<h1>Introduction</h1>
In this project we are trying to fetch data from a source (in this case S3 bucket)
we have manually added the csv files in the S3 bucket to store all the data (e.g. ball by ball data, 
match_data, player_data). We will process and transform the data with Spark for 
better analysis.


#### Architecture Diagram: 
![Architecture_Diagram.png](images%2FArchitecture_Diagram.png)

### Tech Stack
1. Databricks
2. AWS S3
3. Spark
4. SQL
5. Python
6. Data Visualization


### Storage
Data source link: https://data.world/raghu543/ipl-data-till-2017 
Download and store the data in S3 bucket and manage the ACL for the objects.

### Databricks
Sign up for Databricks Community Edition at **databricks.com/try-databricks**
<br>Login at: https://community.cloud.databricks.com/login.html

### Spark with Python engine
Spark Docs: https://spark.apache.org/documentation.html

### Future modifications
1. Upgrade to handle real time data
2. Data Visualization with BI tool