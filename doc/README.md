```shell
sudo docker pull docker.elastic.co/elasticsearch/elasticsearch:8.11.3
sudo docker pull docker.1ms.run/infiniflow/ragflow:v0.16.0-slim

sudo docker save 792fab0c0bd8 > elasticsearch.tar
sudo docker load < elasticsearch.tar

sudo docker compose pull
sudo docker compose up -d
```