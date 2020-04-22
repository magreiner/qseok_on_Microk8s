# Qlik Sense Enterprise on Micro K8s

**repo built in cooperation with Qlik OEM partner Q-nnect AG, Mannheim/Germany**

Whereas the more wellknown "Minikube" is for test and development purposes, Micro Kubernetes (https://microk8s.io/) is 
an autonomous low-ops Kubernetes for clusters and it works on most flavours of Linux. It can also run on multiple nodes and can scale.

## Edit settings.sh

*Before* you start the silent install with <a href="deploy_all.sh">bash deploy_all.sh</a>, make sure you reviewed and corrected the 
<a href="settings.sh">settings.sh</a>, which will be used throughout the installation processes

The scripts will
 - install a local NFS 
 - Docker CE
 - Micro K8s
 - MongoDB
 - Postgres DB 
 - Keycloak Identity Provider
 - QSEoK (Qlik Sense Enterprise on Kubernetes)


