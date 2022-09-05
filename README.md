# NYC-taxi-data-engineering
A data engineering project through which I am learning Airflow, Docker, dbt, Terraform and Spark. As well as improving upon my Big Query/SQL and Kafka skills.
<br>
<br>
I will not be uploading any instructions on how to get various tools up-and-running. 
<br>
But, I will be adding docker-compose.yaml and dockerfile used for some tools like Airflow. Mainly becuase the original hub versions did not work for me and I needed to make some changes for it to start building and running a docker.
<br>
<br>

Other than that, this repo will consist of code - with some specific comments thrown in, that helped me counter errors - Markdown file detailing instructions and flow of the project and the code files itself for the various tools. 
<br>

<br>
In very simple terms:
The project is to download NYC taxi from the web, store it locally temporarily and then upload it to Google cloud storage. From where it will be used in making Datasets/tables/views and those will be used in dbt for analytics engineering. 
Uptil making datasets/tables/views Airflow + Pythonic DAGS -with a little bit of SQL code will be used primarily; run in Docker container
Afterwards dbt on the googel cloud will be utilised.
