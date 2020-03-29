```
helm install --name jenkins --namespace jenkins --set persistence.existingClaim=jenkins-pvc stable/jenkins
```
