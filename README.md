# KubernetesTask


**This repository contains two apps:**
- **BitcoinPrice** :shows the current price of bitcoin and the average price for the last 10 minutes.
- **YnetNews** :displays the latest news from Ynet.

The objective is to deploy the apps in a Kubernetes cluster, it has developed using minikube.


Both apps were dockerized on dockerhub :

![image](https://user-images.githubusercontent.com/96788273/205503828-c7b5fa35-1e36-4f0b-9b1b-6f3244d8b6e1.png)

![image](https://user-images.githubusercontent.com/96788273/205503865-4631ae73-12dd-4a3e-aced-9bdeb55cf840.png)


## **Running The Apps on Minikube:**

1. **Clone This Repository.** : git clone https://github.com/MahaMassalha/KubernetesTask.git

2. **Go to the project directory:** : cd KubernetesTask

3. **Start Minikube:** : minikube start

4. **Enable ingress addon:** : minikube addons enable ingress

5. **Insert deployments:** : kubectl apply -f

6. **Start minikube tunnel:** : minikube tunnel


### **Now you can access the apps from you browser at :** 
##### - http://localhost/ynet

![image](https://user-images.githubusercontent.com/96788273/205508314-088f6ab3-1829-418d-8884-72794d63a3a2.png)


##### - http://localhost/bitcoin

![image](https://user-images.githubusercontent.com/96788273/205508740-cc39bc9e-6f24-49ff-a4f0-33755df03bf0.png)

