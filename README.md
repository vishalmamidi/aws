## configure AWS
```
aws configure
```

## get aws user details

```
aws sts get-caller-identity
```

## list aws eks clusters
```
aws eks list-clusters
```

## generate kubeconfig file for given eks clusters
```
aws eks update-kubeconfig --region region-code --name cluster-name
```

region-codes 
`us-east-1`
`us-east-2`
etc

## get cluster details 
```
kubectl get svc
```
