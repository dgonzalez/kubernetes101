# Setting up the cluster

The first thing you need to know is how to setup a cluster in Google
Cloud Platform.

Google Cloud Platform Container Engine (GKE from now on) is powered by
Kubernetes on a way that, when you setup a closter in GKE, what it is
happening under the hood is that Google is setting up a Kubernetes
cluster for you.

You will find a lot of information in [this](https://cloud.google.com/container-engine/docs/) URL.
but the interesting part is the Quickstart guide. Please follow the
guide in order to setup a cluster.

As you can see, setting up a cluster is fairly trivial. Now you can play
a bit with the interface. In order to reach the interface, please follow
[this](https://cloud.google.com/container-engine/docs/oss-ui) tutorial.

If you have any question, Ricardo, Luke and David are going to be
walking around. Just ask them. They are here to help.

# Considerations

Please avoid creating a massive cluster (2-3 machines with around 1GB of
RAM should be more than enough).
