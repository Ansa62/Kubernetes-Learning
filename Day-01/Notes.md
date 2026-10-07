Cluster
The entire Kubernetes environment.

Node
A machine/VM that runs workloads.

Pod
The smallest deployable unit in Kubernetes. Usually contains one application container.

Container
Your actual application running inside the Pod.

Deployment
Manages Pods and makes sure the desired number of replicas are running.

Kubernetes:
Kubernetes is a system that manages the entire application container through deployments.

What happens if a Pod crashes?

The controller responsible for maintaining the desired number of replicas creates/replaces the Pod.

What's the difference between a Pod and a container?

A container runs the application; a Pod is the Kubernetes execution unit that encapsulates one or more containers.

What is a Service?

A stable network endpoint that allows traffic to reach Pods

What's the relationship?
Deployment
↓
ReplicaSet
↓
Pod
↓
Container


