# nginx-geoipfilter

## Purpose of this repo

As part of making our instance of NGINX deployable in order to improve our ability to maneuver the service to combat server instability or total loss of function, important configurations have been extracted from previous servers and hosted here - sensitive information is not hosted in this public repo, and are inserted at time of deployment.

## Installing the contents of this repo

This repository is installed to a previously configured NGINX server automatically during deployment.

In a case where this needs to be installed manually, you will have to acquire the appropriate information for the variables - anything contained in #( ) - separately, on top of a manual install of NGINX.

This service is an intermediary to a number of our other services, and will be difficult to test locally. Contact Ops if you have any questions about this particular function or if you need to work on this for any reason (CCRs, etc.).
