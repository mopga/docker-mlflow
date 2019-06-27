# docker-mlflow
Dockerfile for MLflow platform testing in local development

1. docker pull mopga/mlflow

2. docker run -d --network=host mopga/mlflow

3. log into docker container and make you experiments:
    - docker exec -ti %container_name% bash

4. all examples are in /mlflow/github/examples/ dir

5. after running examples you can open in your broser the URL http://localhost:5000/ and see the experiments results.