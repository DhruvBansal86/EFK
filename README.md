# EFK
This repo is for Elasticsearch, Fluentd and Kibana cluster creation using Kubernetes

In Ingress.yml :- Make sure to give DNS name of the load balancer end point otherwise you can launch kibana with type load balancer to server at 80 port

password.yml :- username=elastic, password= elastic

nginx.yml and nginx-service.yml :- To test and validate flow of logs to kibana. you can hit url endpoint and check that in Kibana

storage.yml :- This will create a storage class in Azure
