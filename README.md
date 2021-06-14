[![Build status](https://dev.azure.com/natan-dias/Kube-tools/_apis/build/status/Kube-tools-CI)](https://dev.azure.com/natan-dias/Kube-tools/_build/latest?definitionId=8)

# Kube Tools

Docker image with tools for Kubernets administration and Debug.

## Latest version features:

+ Kubectl CLI
+ httping
+ nmap
+ jq (JSON Processor)

## Docker Hub Repo

To use this image in Docker or Podman:

> docker pull natandias1/kube-tools:TAG (you can use "latest" TAG)
>
> podman pull natandias1/kube-tools:TAG (you can use "latest" TAG) 

## Kubernetes

To use in kubernetes: Use YAML file!

> kubectl apply -f ktools.yaml
>
> kubectl attach -n ktools -it ktools
