# Kubernetes (K8s) Task #
### K8s Task – MCQs ###


### Q1. What is the smallest unit that Kubernetes deploys?

ans -> B. pod


### Q2. Which Kubernetes object is used to expose pods to network traffic?

ans -> C. service

### Q3. Which Service type is used only for internal communication inside the cluster?

ans -> C. ClusterIP

### Q4. You want to access an application using <NodeIP>:<Port> 

ans -> B. NodePort

### Q5. Which Service type is mainly used in cloud environments to expose applications externally?

ans -> C. LoadBalancer

### Q6. A pod is deleted accidentally. Which pod type can automatically recreate it?

ans -> C. Pod managed by Deployment

### Q7. Which pod type is used to run initialization tasks before the main container starts?

ans -> B. Init Pod

### Q8. Containers inside the same pod communicate using:

ans -> C. Same IP address

### Q9. Which Service assigns a stable internal IP address automatically?

ans -> C. ClusterIP

### Q10. You created a Service, but traffic is not reaching the pod.What is the most common reason?

ans -> B. Label mismatch

### Q11. Which Kubernetes component provides DNS-based service discovery?

ans -> C. CoreDNS

### Q12. You want a pod to always run on a specific node

ans -> C. Static Pod

### Q13. Which Service type exposes a fixed port on every node?

ans -> B. Nodeport

### Q14. You want pods inside the cluster to access an application using a DNS name. Which Service type should you use?

ans -> c. clusterIP

### Q15. Which command shows the IP address of a pod?

ans -> C. kubectl get pods -o wide

### Q16. You created a LoadBalancer Service in a local cluster

ans -> B. External IP stays pending

### Q17. Which pod type is commonly used to support a main application with logging or monitoring?

ans -> C. Sidecar Pod

### Q18. Which Service field decides which pods receive traffic?

ans -> C. selector

### Q19. Which command is used to list all Services in a namespace?

ans -> A. kubectl get pods

### Q20. Two pods in the same namespace want to communicate. What is the recommended Kubernetes way?
     
ans -> B. Use Service name


# Practical Assignment #

## Task: ##

You are given an application image that runs a web server.
Perform the following steps:

### 1.Create a Deployment that runs the application with at least 2 pods.

![](./img/Screenshot%20(213).png)

### 2.Ensure all pods are created successfully and are in Running state.


![](./img/Screenshot%20(212).png)



### 3.Create a NodePort Service to expose the application.


![](./img/Screenshot%20(214).png)

![](./img/Screenshot%20(216).png)

### 4.Access the application from a browser using:
http://`<NodeIP><NodePort>`

- Open browser and navigate to: http://`<NodeIP>`:30007

### 5.Verify that the application output is  visible in the browser.

### 6.Take a screenshot of the browser output.

![](./img/Screenshot%20(215).png)


# README.md File Requirements #
### 7.Create a README.md file and add:

* Deployment name: `web-app`

* Service type used: `NodePort`

* URL used to access the application

  http://`<NodeIP>`:30007

* Screenshot of the browser output


![](./img/Screenshot%20(215).png)

### 8.Push the README.md file to a Git repository and submit the repository link.

![](./img/Screenshot%20(217).png)


