# blog-k8s-simple-app
First half of https://www.udemy.com/course/microservices-with-node-js-and-react/ course

### Reqs:
* docker
* kubernetes
* kubectl
* ingress-nginx plugin
* skaffold
* add local routing rule 127.0.0.1 -> ports.com for ingress service to correctly detect traffic to app

##### Links:
* https://kubernetes.github.io/ingress-nginx/kubectl-plugin/
* https://skaffold.dev/docs/install/

### Then run 
```
$ kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.40.2/deploy/static/provider/cloud/deploy.yaml
```
### and finnaly 
```
$ skaffold dev 
```
