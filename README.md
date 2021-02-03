# jenkins_helm
This repository has the helm chart for the jenkins deployment
This project was created with the help of the [helm chart ](https://github.com/jenkinsci/helm-charts/tree/main/charts/jenkins)
 
## Steps
- Clone this repository and we will deploy the jenkins to a EKS cluster
- Then run the helm command to install the chart
```helm install jenkins -f values.yaml .```
- To expose the Jenkins application on internet via EKS, we select the Loadbalancer service. Then the ELB DNS can be used to access.
