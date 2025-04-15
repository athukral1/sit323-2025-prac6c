Tech Stack:
•	GitHub
•	Visual Studio
•	Node.js
•	Docker
•	Kubernetes 
•	Kubernetes CLI (kubectl) 

Code Overview:
Building on the Kubernetes deployment finished in work 6.1P, this work focuses on using the Kubernetes CLI and web interface to communicate with the deployed Node.js microservice. Verifying the application's availability within the Kubernetes cluster and exposing it for local access via port forwarding are the main goals. Previously containerized with Docker and deployed using ReplicaSet and Kubernetes Deployment, the microservice is now made available via a Kubernetes Service. Kubectl port-forward is used to safely map a local port to the service's target port, and a ClusterIP service is established to expose the application inside within the cluster. This enables users to utilize localhost to visit the microservice from a web browser.
