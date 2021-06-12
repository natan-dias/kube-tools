# Kube Tools

Docker image with tools for Kubernets administration and Debug.

## version 0.1 features:

+ Kubectl CLI
+ httping
+ nmap

## Docker Hub Repo

To use this image in Docker, Podman or Kubernetes

> natandias1/kube-tools:TAG

## Kubernetes

To use in kubernetes. Use YAML file.

> kubectl apply -f ktools.yaml
>
> kubectl attach -n ktools -it ktools