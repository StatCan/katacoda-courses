Here are some example commands using the K3s cli to inspect the cluster configuration.

Get the cluster information:

`k3s kubectl cluster-info`{{execute T2}}

Get the Nodes in a cluster:

`k3s kubectl get node`{{execute T2}}

View all of the pods running:

`k3s kubectl get pods --all-namespaces`{{execute T2}}

Set an alias for `k3s kubectl` to k:

`alias k="k3s kubectl"`{{execute T2}}

You can now use:

`k get pods --all-namespaces`{{execute T2}}

> Note: All future modules in this pathway will have this setup by default for you.
