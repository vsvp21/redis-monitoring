<h1>Redis Monitoring with prometheus and grafana</h1>


<h2>Installation:</h2>

- docker-compose up -d
- Next, go to grafana (http://localhost:3000)
- After that, create new data source in configurations -> data sources -> add data source
- Choose prometheus
- Fill in http://prometheus:9090 as the URL
- Click save & test
- Then click "+" and select import
- Finally, Enter this dashboard's id https://grafana.com/grafana/dashboards/763