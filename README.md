# cloud-concepts

## networking topics
- shared vpc
![image info](./images/svpc-overview.drawio.png)
- private services access
- vpc network peering
![image info](./images/vpc-network-peering.drawio.png)
  - firewall (target at node)
- serverless vpc
- vpc service control

## GKE
- Kubernetes components
![image info](./images/gke-components.drawio.png)
- private gke network 
![image info](./images/private-gke.drawio.png)

quoted from https://cloud.google.com/kubernetes-engine/docs/concepts/private-cluster-concept#the_control_plane_in_private_clusters

Traffic between nodes and the control plane is routed entirely using internal IP addresses. If you use VPC Network Peering to connect your cluster's VPC network to a third network, the third network cannot reach resources in the control plane's VPC network. This is because VPC Network Peering only supports communication between directly peered networks, and the third network cannot be peered with the control plane network.
![image info](./images/accessing-private-gke.drawio.png)
- service mesh with Istio
  - service networking