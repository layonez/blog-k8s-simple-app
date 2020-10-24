# blog-k8s-simple-app
First half of https://www.udemy.com/course/microservices-with-node-js-and-react/ course

### Reqs:
* ingress-nginx plugin
* skaffold
* docker
* kubernates
##### Links:
* https://kubernetes.github.io/ingress-nginx/kubectl-plugin/
* https://skaffold.dev/docs/install/

### Then run 
```
$ k apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.40.2/deploy/static/provider/cloud/deploy.yaml
```
### and finnaly 
```
$ skaffold dev 
```
