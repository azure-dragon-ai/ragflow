```shell
sudo docker pull docker.elastic.co/elasticsearch/elasticsearch:8.11.3
sudo docker pull docker.1ms.run/infiniflow/ragflow:v0.16.0-slim

sudo docker save 792fab0c0bd8 > elasticsearch.tar
sudo docker load < elasticsearch.tar

sudo docker compose pull
sudo docker compose up -d

git clone https://huggingface.co/datasets/InfiniFlow/medical_QA
GIT_LFS_SKIP_SMUDGE=1 git clone https://huggingface.co/datasets/InfiniFlow/medical_QA

git clone git@hf.co:datasets/InfiniFlow/medical_QA
GIT_LFS_SKIP_SMUDGE=1 git clone git@hf.co:datasets/InfiniFlow/medical_QA
git lfs pull

huggingface-cli
huggingface-cli download
git config credential.helper
source ~/venv3.10/bin/activate
pip install -U "huggingface_hub[cli]"
huggingface-cli --help
huggingface-cli download
brew install huggingface-cli
huggingface-cli login --token $HF_TOKEN --add-to-git-credential

https://hf-mirror.com/datasets/InfiniFlow/medical_QA
```