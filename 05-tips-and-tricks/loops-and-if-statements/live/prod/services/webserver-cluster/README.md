# Web server cluster example (production environment)

Prompt: This folder contains an example Terraform configuration that deploys a cluster of web servers using EC2 and Auto Scaling and a load balancer using ELB in an [Amazon Web Services (AWS) account. The load balancer listens on port 80 and returns the text "Hello, World" for the `/` URL. The code for the cluster and load balancer are defined as a Terraform module in
[modules/services/webserver-cluster](../../../../modules/services/webserver-cluster).
