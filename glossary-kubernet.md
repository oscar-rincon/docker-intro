# Glossary: Kubernetes Basics

| Term                          | Definition                                                                                                           |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------- |
| **Automated bin packing**      | Increases resource utilization and cost savings using a mix of critical and best-effort workloads.                   |
| **Batch execution**           | Manages batch and continuous integration workloads and automatically replaces failed containers, if configured.    |
| **Cloud Controller Manager**   | A Kubernetes control plane component that embeds cloud-specific control logic, allowing integration with cloud providers' APIs. |
| **Cluster**                    | A set of worker machines (nodes) that run containerized applications. Every cluster has at least one worker node.  |
| **Container Orchestration**    | The process of automating the container lifecycle of containerized applications.                                     |
| **Container Runtime**         | The software responsible for running containers.                                                                    |
| **Control Loop**              | A non-terminating loop that regulates the state of a system.                                                         |
| **Control plane**             | The container orchestration layer that exposes APIs to define, deploy, and manage containers.                        |
| **Controller**                | Control loops in Kubernetes that watch the cluster state and make changes to move it closer to the desired state. |
| **Data (Worker) Plane**       | The layer providing capacity (CPU, memory, network, storage) for containers to run and connect to a network.        |
| **DaemonSet**                 | Ensures a copy of a Pod is running across a set of nodes in a cluster.                                               |
| **Declarative Management**     | Expressing the desired state of a resource, allowing Kubernetes to actively maintain the observed state.          |
| **Deployment**                | An object that provides updates for Pods and ReplicaSets, suitable for stateless applications.                    |
| **Designed for extensibility** | Ability to add features to a cluster without modifying source code.                                                  |
| **Docker Swarm**              | A tool for automating the deployment of containerized applications, designed to work with Docker tools.           |
| **Ecosystem**                 | A composition of services, support, and tools available within a given environment or platform.                   |
| **etcd**                      | A highly available key-value store containing cluster data, serving as the source of truth for cluster state.     |
| **Eviction**                  | The process of terminating one or more Pods on Nodes.                                                               |
| **Imperative commands**       | Directly creating, updating, and deleting live objects.                                                              |
| **Imperative Management**     | Defining actions and steps to reach a desired state.                                                                |
| **Ingress**                   | An API object managing external access to services in a cluster, typically for HTTP.                                |
| **IPv4/IPv6 dual stack**      | Assigning both IPv4 and IPv6 addresses to Pods and Services.                                                        |
| **Job**                       | A finite or batch task that runs to completion.                                                                     |
| **Kubectl**                   | The command-line tool for communicating with a Kubernetes cluster's control plane via the Kubernetes API.        |
| **Kubelet**                   | The primary "node agent" running on each node, responsible for managing containers described in PodSpecs.        |
| **Kubernetes**                | An open-source platform for container orchestration, developed by Google and maintained by CNCF.                 |
| **Kubernetes API**            | An application serving Kubernetes functionality through a RESTful interface and storing the cluster state.       |
| **Kubernetes API Server**     | Validates and configures data for Kubernetes API objects (pods, services, etc.) and serves REST operations.     |
| **Kubernetes Controller Manager** | Manages control processes monitoring cluster state and ensuring it aligns with desired state.                  |
| **Kubernetes Cloud Controller Manager** | Embeds cloud-specific control logic, enabling cloud provider API integration.                               |
| **Kubernetes Proxy**          | A network proxy running on each node to maintain network rules allowing communication to Pods in the cluster.   |
| **kube-scheduler**            | A control plane component selecting nodes for pending Pods to run on.                                                |
| **Label Selector**            | Allows filtering resources based on labels.                                                                         |
| **Labels**                    | Tags objects with identifying attributes.                                                                           |
| **Load balancing**            | Balances traffic across Pods for performance and high availability.                                                    |
| **Marathon**                  | An Apache Mesos framework for scaling container infrastructure.                                                        |
| **Namespace**                 | An abstraction for resource isolation within a single cluster.                                                         |
| **Node**                      | The worker machine in a Kubernetes cluster running user applications.                                                 |
| **Nomad**                     | A cluster management and scheduling tool supporting Docker and other applications on various platforms.           |
| **Object**                    | An entity in the Kubernetes system, representing the state of your cluster.                                          |
| **Persistence**               | Ensures an object exists in the system until modified or removed.                                                     |
| **Preemption**                | Logic in Kubernetes helping pending Pods find suitable Nodes by evicting lower-priority Pods.                       |
| **Self-healing**              | Automatically restarting, replacing, rescheduling, or terminating failing or unresponsive containers.               |
| **Service**                   | An abstraction for exposing an application running on a set of Pods as a network service.                            |
| **Service Discovery**         | The process of discovering Pods using IP addresses or a single DNS name.                                              |
| **StatefulSet**               | Manages the deployment and scaling of a set of Pods with guarantees about ordering and uniqueness.                   |
| **Storage**                   | A data store supporting persistent and temporary storage for Pods.                                                     |
| **Storage Orchestration**     | Automatically mounting chosen storage systems for containers.                                                         |
| **Pod**                       | The smallest Kubernetes object, representing a single instance of an application running in a cluster.             |
| **Proxy**                     | In computing, a server acting as an intermediary for a remote service.                                                |
| **ReplicaSet**                | A controller aiming to maintain a set of replica Pods running at all times.                                            |
| **Workload**                  | An application running on Kubernetes.                                                                                |
