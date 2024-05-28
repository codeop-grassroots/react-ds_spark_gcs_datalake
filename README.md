# Apache Spark

## Introduction
Let's test different ways of reading and writing files in Spark


## Getting started

In order to read data from the datalake, you will need to [create a Google Cloud service account](https://cloud.google.com/iam/docs/service-accounts-create#creating), and then [create a key for it](https://cloud.google.com/iam/docs/keys-create-delete). Downoad this key in JSON format and copy it to the `./secrets/` folder.

Additionally, you need to download the Java JAR to enable Spark to read from Google Cloud Storage. You can do it from [here](https://storage.googleapis.com/hadoop-lib/gcs/gcs-connector-hadoop3-latest.jar). Copy this jar in this very folder.

### Requirements
- Docker
- Docker compose

##### With Docker Compose

`````
docker-compose up
`````

You will find the jupyter notebook in [localhost:8888](http://localhost:8888/lab/tree/work/). The password is `codeop`.

### The project

Follow the instructions in the jupyter notebook called `gcs_datalake.ipynb`.
