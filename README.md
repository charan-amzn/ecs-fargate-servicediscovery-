# AWS CloudMap [Service Discovery] with ECS-Fargate
You can find 4 templates in the repository. Run them in this order 
  - cluster-fargate-private-vpc
  - service-discovery-internal 
  - service-fargate-private-subnet-private-discovery
  - cloud9-environment
  
Once everything is created, go to Cloud9 Dashboard, open a terminal and run following commands 
  - dig +short nginx.service.production 
  - curl -v nginx.service.production 
  
