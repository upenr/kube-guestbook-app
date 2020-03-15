# A Kubernetes-deployable application called 'guestbook'

The guestbook example shows how to build a simple multi-tier web application using Kubernetes and Docker. The application consists of a web front end, Redis master for storage, and replicated set of Redis slaves, all for which we will create Kubernetes deployments, pods, and services.

There are two versions of this application. Version 1 (in the `v1` directory) is the the basic guestbook application in go with deployment files for you to exampine at your convenience. Version 2 (in the `v2` directory) extends the guestbook example with additional functionality to call the IBM Watson Tone Analyzer service.


## Prerequisites

* An [IBM Cloud account](http://ibm.biz/Bdz3ru) that is either upgraded with a feature code to trial, paid or subscription.

## Credits

* Tim Robinson, IBM: https://github.com/timroster