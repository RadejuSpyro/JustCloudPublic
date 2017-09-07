# gcloud-simple-ubuntu

Simple deplymennt virtual machine with Linux Ubuntu 16.04 system in Gloogle Cloud Platform. During deployment is creating machine in default network with external IP. Impornt thing to run this deployment is replace "your-project-name" to your name project in GCP before run it.

## Command to deployment
```json
gcloud deployment-manager deployments create simple-ubuntu --config vm.yaml
```

## Author
Piotr Rogala
http://justcloud.pl