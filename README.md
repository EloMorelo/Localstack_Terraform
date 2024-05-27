# Localstack_Terraform
Done on Win10
Opening localstack without docker-compose (recommended) \
docker pull localstack/localstack \
docker run --rm -it -p 4566:4566 -p 4571:4571 localstack/localstack \

Opening localstack using docker-compose \
/path to docker-compose.yml \
compose-docker up -d \
docker run --rm -it -p 4566:4566 -p 4571:4571 localstack/localstack \

/path to terraform project/ <--- Terraform\
terraform init\
terraform plan\
terraform apply\
