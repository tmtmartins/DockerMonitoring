# docker-monitoring
monitoring docker containers using cadvisor, prometheus, redis and grafana
# run - docker-compose up -d
if everything is working good, you should see this message <br>
msg="Server is ready to receive web requests." <br>
check if the containers are running using docker-compose ps
# accessing cadvisor
http://localhost:8080
# accessing prometheus
http://localhost:9090
# accessing grafana
http://localhost:3000
# configure grafana to use prometheus as data source and add the dashboard with the json file 


