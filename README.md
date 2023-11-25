# K8-s

--->>> docker installation

    i have installed the docker 1st 
    then given the permission to the $user=ubuntu to use without the sudo 

--->>> minikube installation

    Step 1: Install curl and kubectl

            Before installing Minikube, you need to install curl and kubectl. You can do this by running the following commands:

                        sudo apt update
                        sudo apt install curl
                        curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
                        sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
                        kubtl version --client

    Step 2: Install Minikube

            Once you have installed curl and kubectl, you can install Minikube by running the following commands:

                        curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
                        sudo i  nsl minikube-linux-amd64 /usr/local/bin/minikube

    Step 3: Start Minikube

            To start Minikube, run the following command:

                        minikube start

                        
