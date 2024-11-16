# minikube
what is minikube?
Minikube is a tool that allows you to set up a single-node Kubernetes cluster on your local computer. It is a great way to experiment with Kubernetes before deploying it in production. Minikube is easy to install and use, and it supports all major operating systems.
Minikube creates a single-node Kubernetes cluster on your local computer. This cluster includes all of the components that are needed to run Kubernetes, such as the API server, the controller manager, and the scheduler. Minikube also includes a Kubernetes client, which you can use to interact with the cluster.
# docker
apt install curl apt-transport-https/n
apt install docker.io
# minikube
wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo cp minikube-linux-amd64 /usr/local/bin/minikube
chmod 755 /usr/local/bin/minikube
# kubectl
curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
chmod +x kubectl
cp kubectl /usr/local/bin/
./kubectl version -o json
sudo usermod -aG docker username 
