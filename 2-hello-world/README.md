# Hello World

In this exercise, we are going to run few images in Kubernetes from the
command line using kubect.

Kubectl is the way to interact with a Kubernetes cluster in order to
create, destroy and reschedule resources. As you could see in our
presentation, resources are the way that Kubernetes has to model the
software world: Pods, Replica Sets, Services...

In this workshop we are going to focus in the basics ones (if you want
more info about Pet Sets, Daemon Sets, Horizontal Autoscalers... please
ask!).

The documentation for Kubectl can be found [here](http://kubernetes.io/docs/user-guide/kubectl-overview/).

Please have a light read on it (just like if you were reading the Argos
catalog).

GKE, relies on the Google Container Registry to push custom images into
Kubernetes. In order to deploy our software, we need to first, build the
Docker Image and then, push it to the Container Registry.

Once this is done, we can use it in our GKE cluster.

Here is one example on how to do it step by step: http://kubernetes.io/docs/hellonode/

Please follow the tutorial and ask us questions. This one can get a bit
tricky as there are few steps involved.
