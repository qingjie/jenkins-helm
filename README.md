```
kubectl apply -f storage-pv-pvc-aws.yaml
helm install --name jenkins --namespace jenkins --set persistence.existingClaim=jenkins-pvc stable/jenkins
kubectl apply -f jenkins_ingress.yaml
```
