LAB - Linux Basics
=====================

A workshop for learning linux basics with basic CLI commands. 

If you already have the Educates operator installed and configured, to
deploy and view this linux basics workshop, run:

```
kubectl apply -f workshop.yaml
kubectl apply -f training-portal.yaml
```

This will deploy a training portal hosting just this workshop. To get the
URL for accessing the training portal run:

```
kubectl get trainingportal/lab-linux-basics
```

The training portal is configured to allow anonymous access.
