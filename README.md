# Introduction
Nginx Ingress controller is a ingress controller used to manage Ingress in Kubernetes.

YAML file taken from https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.12.0/deploy/static/provider/aws/deploy.yaml

Breaking down the nginx ingress controller yaml into 12 parts:
1. namespace
2. service acccounts
3. roles
4. cluster role
5. role binding
6. cluster role binding 
7. configmap
8. service 
9. deployment
10. job
11. ingress class 
12. validating webhook

## Links to nginx ingress documentation
Kubernetes's Documentation on Ingress Controller:
https://kubernetes.io/docs/concepts/services-networking/ingress-controllers/

Kubernetes's Documentation on Nginx Ingress Controller:
https://kubernetes.github.io/ingress-nginx/

Nginx Ingress Examples:
https://kubernetes.github.io/ingress-nginx/examples/

NGINX Ingress controller with Helm:
https://docs.nginx.com/nginx-ingress-controller/installation/installing-nic/installation-with-helm/

If using EKS + ALB, use aws load balancer controller
- https://kubernetes-sigs.github.io/aws-load-balancer-controller/v2.4/
- To use ALB + nginx ingress -> use nodeport

AWS' article on using nginx ingress controller + NLB:
https://aws.amazon.com/blogs/containers/exposing-kubernetes-applications-part-3-nginx-ingress-controller/

AWS LB ingress controller reference:
https://kubernetes-sigs.github.io/aws-load-balancer-controller/v2.4/
