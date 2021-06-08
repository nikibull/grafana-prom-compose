Project deployment grafana+prometheus with docker-compose

install node_exporter:

wget https://github.com/prometheus/node_exporter/releases/download/v0.18.1/node_exporter-0.18.1.linux-amd64.tar.gz

tar -xzvf node_exporter-0.18.1.linux-amd64.tar.gz -C /usr/local/bin

cd /usr/local/bin/node_exporter-0.18.1.linux-amd64

./node_exporter
