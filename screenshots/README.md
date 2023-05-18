# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
Image evidence : 
DockerHud.PNG

* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)
Image evidence : 
GitHud_Project3.PNG

* Travis CI showing a successful build and deploy job
I used Circleci CI showing a successful build and deploy job instead of Travis CI 
Image evidence : Circleci_Build.PNG

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods

Image evidence : 
kubectl_get_pods.PNG
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services

Image evidence : 
kubectl _describe _services_1.PNG
kubectl _describe _services_2.PNG
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa

Image evidence :
kubectl _describe _services_1.PNG
kubectl _describe _services_2.PNG
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}

Image evidence : 
kubectl_logs_pod.PNG
```
