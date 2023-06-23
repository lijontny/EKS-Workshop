# EKS-Workshop
### Lab Setup
1. Collect Event ID from the AWS team
2. Connect to AWS Workshop studio as per instruction [here](https://catalog.us-east-1.prod.workshops.aws/workshops/ed1a8610-c721-43be-b8e7-0f300f74684e/en-US/setup/workshop-studio/setup)
3. Sign in to the [AWS Cloud9 console](https://console.aws.amazon.com/cloud9/). 
4. Launch your Cloud9 IDE, Follow instructions [here](https://catalog.us-east-1.prod.workshops.aws/workshops/ed1a8610-c721-43be-b8e7-0f300f74684e/en-US/setup/workshop-studio/launching-cloud9)
5. Update Cloud9 IAM setup for the workshop, Follow instructions [here](https://batch.hpcworkshops.com/02-preparation/06-iam-roles.html)
6. Create an SSH-Key, Follow instructions [here](https://catalog.workshops.aws/containers/en-US/setup/createsshkey)
### Deploy EKS Cluster

1. export AWS_REGION=eu-west-1
2. [Prerequisites](https://catalog.us-east-1.prod.workshops.aws/event/dashboard/en-US/workshop/eks/launch-eks/prerequisites)
3. Create an SSH-Key, Follow instructions [here](https://catalog.workshops.aws/containers/en-US/setup/createsshkey)
4. Launch an Amazon EKS cluster, Follow instructions [here](https://catalog.us-east-1.prod.workshops.aws/event/dashboard/en-US/workshop/eks/launch-eks/launcheks)
5. Test the Cluster, [Link](https://catalog.us-east-1.prod.workshops.aws/event/dashboard/en-US/workshop/eks/launch-eks/test)

### Preparing EKS for Application deployment
1. Provision AWS Load Balancer Controller - Follow instructions [here](https://catalog.us-east-1.prod.workshops.aws/event/dashboard/en-US/workshop/eks/setup-environment/setup-ingress)
2. Deploy the Official Kubernetes Dashboard - Follow instructions [here](https://catalog.us-east-1.prod.workshops.aws/event/dashboard/en-US/workshop/eks/setup-environment/dashboard)

### Application Deployment
1. About Workshop Application - [Readme](https://catalog.workshops.aws/eks-immersionday/en-US/aboutworkshopapp)
2. Deploy the Helm chart and test the application, Follow instructions [here](https://catalog.workshops.aws/eks-immersionday/en-US/helm/deploy)
