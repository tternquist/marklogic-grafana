

Before running docker compose, run the following:

    mkdir -p ./volumes/loki
    sudo chown 10001:10001 ./volumes/loki

    mkdir -p ./volumes/grafana
    sudo chown 472:472 ./volumes/grafana

Docker Compose Command: 
    `docker compose -f "docker-compose-3-node-grafana.yml" up -d --build `

Based on guide - https://cylab.be/blog/241/use-loki-to-monitor-the-logs-of-your-docker-compose-application



To access Grafana use http://localhost:3000
To access ML cluster use http://localhost:8000,8001, etc.


