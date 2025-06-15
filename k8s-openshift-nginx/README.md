``` 
oc apply -f nginx-deployment.yaml
oc apply -f nginx-service.yaml
oc apply -f nginx-route.yaml
```

``` 
oc get route nginx-route
```