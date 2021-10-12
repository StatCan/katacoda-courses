## Setup

Install K3s via the official installer:

`curl -sfL https://get.k3s.io | INSTALL_K3S_VERSION=v1.22.2+k3s2 sh -`{{execute}}

You can now instantiate a new cluster using the following command:

`k3s server`{{execute T1}}
