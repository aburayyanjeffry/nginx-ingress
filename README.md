# nginx-ingress
nginx-ingress

This is step by step on how to deploy nginx-ingress controller, few sample applications (nginx webserver, tomcat and apache webserver) and ingress resouces. These YAML are to be use with [this blog](https://www.endpointdev.com/blog/)
```bash
kubectl apply -f 01-ingress-controller.yaml
kubectl apply -f 02-nginx-webserver.yaml
kubectl apply -f 03-tomcat-webappserver.yaml
kubectl apply -f 04-httpd-webserver.yaml
kubectl apply -f 05-ingress-resouce.yaml
```


