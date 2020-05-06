# Qlik Sense Enterprise on Micro K8s/Ubuntu

**repo built in cooperation with Qlik OEM partner Q-nnect AG, Mannheim/Germany**

Whereas the more wellknown "Minikube" is for test and development purposes, Micro Kubernetes (https://microk8s.io/) is 
an autonomous low-ops Kubernetes for clusters and it works on most flavours of Linux. It can also run on multiple nodes and can scale.

## Edit settings.sh

*Before* you start the silent install with <a href="deploy_all.sh">bash deploy_all.sh</a>, make sure you reviewed and corrected the 
<a href="settings.sh">settings.sh</a>, which will be used throughout the installation processes

The scripts will
 - install a local NFS (Network Filesystem)
 - Docker Community Edition
 - MicroK8s
 - MongoDB Community Edition
 - A local identity provider (Keycloak https://www.keycloak.org/) and Postgres for persistance
 - QSEoK (Qlik Sense Enterprise on Kubernetes)

## Installation 
 - To get it run `git clone https://github.com/ChristofSchwarz/qseok_on_Microk8s`
 - To launch it go to `cd qseok_on_Microk8s/` 
 - Make sure you edit the `settings.sh` file to match your system
 - Then run `sudo bash deploy_all.sh`
 
 

