## setup

1. sudo sysctl -w vm.max_map_count=262144 <br />
2. mkdir -p ./elasticsearch/data <br />
3. sudo docker compose up -d
4. https://docs.fluentd.org/container-deployment/docker-compose >> follow up step4