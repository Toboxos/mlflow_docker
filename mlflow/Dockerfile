ARG MLFLOW_VERSION=3.1.0
FROM ghcr.io/mlflow/mlflow:v${MLFLOW_VERSION}
RUN pip install mlflow[auth]
ENTRYPOINT [ "mlflow" ]