# KubernetesTask


**This repository contains two apps:**
- **BitcoinPrice** :shows the current price of bitcoin and the average price for the last 10 minutes.
- **YnetNews** :displays the latest news from Ynet.

The objective is to deploy the apps in a Kubernetes cluster, it has developed using minikube.


Both apps were dockerized on dockerhub :

![image](https://user-images.githubusercontent.com/96788273/205503828-c7b5fa35-1e36-4f0b-9b1b-6f3244d8b6e1.png)

![image](https://user-images.githubusercontent.com/96788273/205503865-4631ae73-12dd-4a3e-aced-9bdeb55cf840.png)


## **Running The Apps on Minikube:**

1. **Clone This Repository.**
- git clone https://github.com/Dima-Nakhleh/Kubernetes-Ingress.git
2. **Go to the project directory:**
- cd Kubernetes-Ingress
3. **Start Minikube:**
- minikube start
4. **apply deployment:**
- kubectl apply -f .
5. **Enable ingress addon:**
- minikube addons enable ingress
6. **Start minikube tunnel:**
- minikube tunnel



[![https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/get%20po3.GIF](https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/get%20po3.GIF "https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/get%20po3.GIF")](https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/get%20po3.GIF "https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/get%20po3.GIF")

## **You can now access the apps from you browser at :** 
## - http://localhost/ynet

[![https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/ynet.GIF](https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/ynet.GIF "https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/ynet.GIF")](https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/ynet.GIF "https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/ynet.GIF")

## - http://localhost/bitcoin

[![https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/bitcoin.GIF](https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/bitcoin.GIF "https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/bitcoin.GIF")](https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/bitcoin.GIF "https://github.com/Dima-Nakhleh/Kubernetes-Ingress/blob/main/images/bitcoin.GIF")
