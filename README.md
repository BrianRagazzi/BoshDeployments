# BOSH Deployments

This is just a collection of hints for deploying to BOSH
### Key Objectives ###
* (Most if not all) Credentials, certificates and keys must be stored in credhub
* TLS must be enabled for deployed apps and services

## Starting Position
* Deployed Pivotal Ops Manager v2.5+ (obtained the SSH private key)
* Deployed BOSH director
* Latest (or nearly latest) Xenial stemcell uploaded to Director

## Configure Credhub 
