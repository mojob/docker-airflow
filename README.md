This is a fork of [docker-airflow](https://github.com/puckel/docker-airflow)

We have added: 
* opencv for working with video and images + 
* Docker to create deployable docker images (dind)
* Boto to connect with aws s3
* s2i to create deployable machine learning models with seldon
* Kubectl and Kops to deploy s2i images with seldon deployment
