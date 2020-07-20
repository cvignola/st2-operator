# st2-operator
Sample install operator for st2 based on operator sdk 

## Build 

From project root issue:

```
./build/build.sh

Note: script is hard coded for cvignola git user id.  Modify to taste. 
```

## Install 

From project root: 

```
kubectl create namespace st2 
kubectl apply -f deploy -n st2 
```
