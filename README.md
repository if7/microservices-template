# Environment Setup

## Install Docker and Kind
I am using fedora and here are the instructions for fedora.

Follow the guides to install [docker](https://docs.docker.com/engine/install/fedora/) and [kind](https://kind.sigs.k8s.io/docs/user/quick-start/)

## Create cluster using

```
    kind create cluster --config environment/kind-config.yaml
``` 