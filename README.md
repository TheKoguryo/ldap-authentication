# ldap-authentication
Kubernetes Authentication with LDAP - Soup to Nuts
* create namespace: kube-authentication
* Edit host section of the script 1 with you Ip addresses
* run cert process scripts 1-3
* run all  ldap yaml
* run all phpldapadmin yaml
* run all gangway yaml
* modify gangway configmap
* Reapply gangway-configmap
* run all dex yaml
* modify dex configmap
* Reapply dex configmap
* Apply the API flags and load the cert see api-server-setup.txt


* Create user using phpadmin http://<Kubeadmin worker node ip>:31000
* Login to gangway http://<Kubeadmin worker node ip>:32000
