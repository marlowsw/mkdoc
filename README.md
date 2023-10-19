# mkdoc
mkdocs kubernetes deployment
#create deployment.yaml
oc create -f doployment.yaml
#port-forward
oc port-forward "pod-name" 8888:80
http://localhost:8888
