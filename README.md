# Intro-to-Airflow
Introduction to Airflow (Yaml File,Data Pipeline scheduling and Databases)

YAML FILE:
Contains all the executables required to run Airfloe on Docker

DOCKER IMAGE:
Creates a docker Image and container on port 8080, use (localhost:8080) for airflow ui on browser
Username and password is set as airflow default.

DAGS:

user_processing:

it gives a glimpse of how the airflow is used for scheduling dependable tasks.

The hooks and operators work together to complete below flow easily

create_table >> is_api_available >> extract_user >> process_user >> store_user

Group Dag:
Combines multiple worflows to one




