# ECS
- ECS Container service setup cloudFormation template. Allows creation of a ECS cluster in existing VPC
- Load Balancer (ALB ) is setup and registered with SSL certificate. 
- Userdata is fed for setup of NewRelic and SumoLogic for logging allowing to capture key log files
- The Task definition and service definition is defined allowing application to digest docker images from ECR
- Finally in the output you get ECS URL for management
