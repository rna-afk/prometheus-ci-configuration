# OpenShift Installer Prometheus CI configuration

This is a boilerplate code that have the deployment yaml files for the prometheus
and the aggregation gateway containers that can be easily deployed to any cluster
required.

## Quick Start

First, login to the openshift cluster that you want to deploy the prometheus and the
prometheus aggregation gateway

Clone this repository. Then, run

```sh
oc create -f .
```

This will create the deployment with 2 containers, one for the prometheus instance and 
one for the aggregation gateway, a service to expose the two containers and 2 routes to
provide an external link for these instances.
