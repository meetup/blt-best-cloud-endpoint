# BLT Best Cloud Endpoint

Example K8s cloud-endpoint project.

## The project

This project is a very simple node application.
In order to avoid building a docker artifact the
index.js is inside of our configmap
[infra/deployment-cm.yaml](infra/deployment-cm.yaml)

The index.js will return 500 if the env var
`FAIL_REQUEST` is set to true.
