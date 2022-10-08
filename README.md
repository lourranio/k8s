# k8s

1. Simulador
https://killer.sh/

<div>
  <span align="center">
  <img alt="logo-ls" title="logo-ls" src="https://github.com/lourranio/k8s/blob/c4fe256bf4af6896b3a5b603ccb5e82f0c9bdf82/img/logo_killersimulator.png">
    </span>
</div><br>

[![Watch the video](https://img.youtube.com/vi/nTQUwghvy5Q/default.jpg)](https://www.youtube.com/watch?v=KfrZd9YCftU)


5. Service & Network
 * https://kubernetes.io/docs/concepts/services-networking/service/ 
 * https://kubernetes.io/docs/concepts/services-networking/service/#type-nodeport 
 * https://kubernetes.io/docs/concepts/services-networking/service/#loadbalancer
 * https://kubernetes.io/docs/concepts/services-networking/ingress/
 * https://kubernetes.github.io/ingress-nginx/deploy/
 * 


# Kubernetes for the Absolute Beginners - Hands-on Tutorial

##  Setup Kubernetes 
### References 

Install and set up the kubectl tool: –

https://kubernetes.io/docs/tasks/tools/

Install Minikube: –

https://minikube.sigs.k8s.io/docs/start/

Install VirtualBox: –

https://www.virtualbox.org/wiki/Downloads

https://www.virtualbox.org/wiki/Linux_Downloads

Minikube Tutorial: –

https://kubernetes.io/docs/tutorials/hello-minikube/

If the minikube installation has been done on the macOS, then to access the URL on the local browser, we need to do a few steps to get the service URL to work. Those steps are covered on this documentation page: –

https://minikube.sigs.k8s.io/docs/handbook/accessing/#using-minikube-service-with-tunnel


## Kubernetes Concepts 

### A note about creating Pod

A note about creating Pods

A note about creating pods using kubectl run.

To create a pod from the command line, use the command:

Create an NGINX Pod

```kubectl run nginx --image=nginx```

As of version 1.18, kubectl run (without any arguments such as --generator ) will create a pod instead of a deployment.

To create a deployment using imperative command, use kubectl create:

```kubectl create deployment nginx --image=nginx```

Kubernetes Concepts – https://kubernetes.io/docs/concepts/

Pod Overview- https://kubernetes.io/docs/concepts/workloads/pods/pod-overview/

