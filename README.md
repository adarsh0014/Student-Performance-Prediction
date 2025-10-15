### End to End Data Science Project
import dagshub
dagshub.init(repo_owner='adarsh0014', repo_name='Student-Performance-Prediction', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)