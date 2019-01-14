# kubernetes-network-policies

## NetworkPolicy
Network Policies define which traffic flow is allowed between groups of pods and other network resources
The NetworkPolicy resource uses labels to select pods to which the policy would apply to
Scope of a network policy is usually a namespace. However, it is possible to allow traffic from other namespaces

## Prerequisites
To be able to use network policies, you need to be using a network plugin which supports the NetworkPolicy functionality. Examples of networks which support network policies are:

* Weavenet
* Calico
* Cilium
* kube-router
* Romana
