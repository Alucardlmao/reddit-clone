> # Prerequisite For Deployment of a Reddit Copy on Kubernetes with Ingress Enabled


1. EC2 ( AMI- Ubuntu, Type- t2.medium )

2. Docker

3. Minikube

4. kubectl

# Steps:-

# For Docker Installation
```python
sudo apt-get update
sudo apt-get install docker.io -y
sudo usermod -aG docker $USER && newgrp docker
```

# For Minikube & Kubectl
```python
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube 
```

```python
sudo snap install kubectl --classic
minikube start --driver=docker

```