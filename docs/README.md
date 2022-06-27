```shell
cd docker

sudo docker-compose up -d jianmu-mysql
sudo docker-compose up -d ci-server
sudo docker-compose up -d worker
sudo docker-compose up -d web

sudo docker-compose up -d
sudo docker-compose down

sudo docker-compose logs -f

kubectl apply -f kubernetes.yaml
```