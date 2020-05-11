### AWS ELB ECS

`aws cloudformation create-stack --template-body file://app-elb-ecs-cluster.yml --stack-name app-cluster --capabilities CAPABILITY_NAMED_IAM`
`aws cloudformation create-stack --template-body file://services/product-service.yml --stack-name product-serivce`
`aws cloudformation create-stack --template-body file://services/hello-world-service.yml --stack-name hello-world-serivce`
