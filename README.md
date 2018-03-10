# Azure Stack, DOcker and Kubernetes scratchPad for Ron

## What it is?

This is a list of links to learn Docker and Kubernetes during Mani's onsite visit with Ron.


### [Free AKS Workshop](https://github.com/Azure/blackbelt-aks-hackfest/)

### [Julia's Kubernetes Cartoon](https://jvns.ca/blog/2017/06/04/learning-about-kubernetes/)

### [Install Docker on Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/)

Here is an excerpt on how to install Docker on Kubernetes.

Update apt repository

```sh
sudo apt-get update
```

Install packages to allow **apt** to use a repository over HTTPS:
```sh
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    software-properties-common
```
