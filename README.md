# helm_template
Basic Helm Template.
kubectl create deployment my-website --image nginx --dry-run -o yaml >deployment.yaml
..
helm install --name my-website . 
helm delete  my-website
