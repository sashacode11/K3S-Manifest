Steps create kubernetes :
1. Create mongo pv and pvc to store data
2. Create secret for mongodb(backend) and mongo-express(frontend)
3. Create mongodb and mongo-express deployment and service and configmap

Kubernetes run on Jenkins steps:
1. Create those above in 1 file
2. Create spacename
3. Create role 
4. Create token call secret for this spacename
