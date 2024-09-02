airflow commands 

- create python virtual env
python3 -m venv py_env

- activate python env 
source py_env/bin/activate 

- run airflow scheduler 
airflow scheduler

- set airflow home 
export AIRFLOW_HOME=/Users/ravipal/Desktop/Workspace/airflow_tutorial/airflow

- to run server 
airflow webserver -p 8080

- to create users 
airflow users create \
          --username admin \
          --firstname FIRST_NAME \
          --lastname LAST_NAME \
          --role Admin \
          --email admin@example.org

airflow users create --username admin --firstname admin --lastname admin --role Admin --email admin@domain.com

password - ravi1408