# Advanced Kubernetes

Now that you have completed the previous exercises, it is time for you
to work on a system from scratch.

In this case, we are going to use as a base [this](https://github.com/dgonzalez/google-dev-fest-2016) repository which, is a microservices
system that outputs the iso formatted and the utc current date in a rest API fashion.
using an [aggregator pattern](http://www.enterpriseintegrationpatterns.com/patterns/messaging/Aggregator.html).

Deploy it to Kubernetes. If you need any help with it don't be afraid to
ask!

Now that you have the system running, we need to improve few things in
it:

- We want antoher service that outputs the Unix timestamp.
- We also want to have the current time in `Ittoqqortoormiit` and `Pitcairn Island` as they seem very crowded places.
- Another fantastic piece of work would be give a simple UI to the
  service and remodel the architecture on a way that the API is not
exposed anymore but the UI is (this is challenging for a day, so feel
free to "customise it").

Once you have completed the work from the previous steps, we want to
deploy the new system in the cluster but we don't want to interrupt the
service. In order to do it, we are going to use the [Rolling Updates](http://kubernetes.io/docs/user-guide/rolling-updates/)
capabilities built in Kubernetes.

**BONUS**: Create a [JMeter](http://jmeter.apache.org/usermanual/build-web-test-plan.html) test plan (or similar) to keep pooling the URL of
the deployed API while the Rolling Update is being executed to see how
the service is always up.
