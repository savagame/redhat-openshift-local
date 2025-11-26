# RedHat OpenShift Local

## Setup

you should install crc on your local pc, minimal system requirements: 16~GB ram, 100GB free stroage space, 6 core cpus.

```
crc setup
crc start --cpus 6 --memory 12228
crc console --credentials
oc new-project demo-basic
oc get project
oc apply -f app.yaml
oc get pods
oc get deployments
oc delete deployment my-deployment
```
