## MLFLOW PROJECT

import dagshub
dagshub.init(repo_owner='NairDeepesh', repo_name='MLFlowProject', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)