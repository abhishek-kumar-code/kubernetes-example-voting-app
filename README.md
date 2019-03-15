# kubernetes-example-voting-app

 Step 1 Login to Google Cloud Platform. Go to Kubernetes Engine and create a cluster. Once the cluster is running, avtivate the console.

 Step 2 Clone the desired repository from GitHub.

 Step 3 Creating Pods and Services

`kubectl create -f voting-app-pod.yml`

`kubeclt create -f voting-app-service.yml`

`kubectl create -f redis-pod.yml`

`kubeclt create -f redis-service.yml`

`kubectl create -f postgres-pod.yml`

`kubeclt create -f postgres-service.yml`

`kubectl create -f worker-app-pod.yml`

`kubectl create -f result-app-pod.yml`

`kubeclt create -f result-app-service.yml`

// To check all the Pods

`kubectl get pods`

// To check all the Services

`kubectl get services`

![alt text](http://url/to/img.png)

