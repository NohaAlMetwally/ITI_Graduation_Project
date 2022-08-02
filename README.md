# ITI_Graduation_Project

### For the terraform code
  * $ terraform init
  * $ terraform plan
  * $ terraform apply

### Build Docker image for the pyhton app from the Dockerfile, and upload the image to docker hub
  * $ docker build -t image-name .
  * $ docker tag image-name your-docker-repo
  * $ docker push your-docker-repo

### SSH to the private VM:

### Install kubectl
  * $ sudo apt-get update
  * $ sudo snap install kubectl --classic
  * $ kubectl --help

### authorize gcloud to access the Cloud Platform with Google user credentials
  * $ gcloud auth login

### SSH to GKE
  * $ kubectl create namespace
  * $ kubectl create -Rf jenkins-dep
  * $ kubectl get svc -n namespace-name

### get the load balancer IP and port to access jenkins throgh browser 
  * to get jenkins bath exec to the pod
  * $ kubectl get pods -n namespace
  * $ kubectl exec -it -n namespace pod-id /bin/sh
  
### open jenkins and create new item, type pipeline, use this repo 
* https://github.com/NohaAlMetwally/simple-hello-app.git

![Untitled2](https://user-images.githubusercontent.com/13887135/182382072-d7ee3d65-bc35-4530-8b92-8385007a1b3a.png)

![final4](https://user-images.githubusercontent.com/13887135/182176525-1d7f302f-26f4-452d-ab70-9732cfb0c47e.png)


  
  


