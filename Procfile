# On first run, to let the app initialize the DB...
#   web: AIRFLOW__CORE__SQL_ALCHEMY_CONN=${DATABASE_URL} airflow initdb
# Then: 
web: AIRFLOW__CORE__SQL_ALCHEMY_CONN=${DATABASE_URL} airflow webserver --port $PORT
scheduler: AIRFLOW__CORE__SQL_ALCHEMY_CONN=${DATABASE_URL} airflow scheduler
