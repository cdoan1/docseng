Demo Clusters
-------------

Cluster API address
https://api.released.demo.red-chesterfield.com:6443
Console URL
https://console-openshift-console.apps.released.demo.red-chesterfield.com
Username/password
kubeadmin / (https://google.com)[password]

## Cluster Name: **${name}**  
**Build Date:** $(awk -F'"' 'NR==1{ print $2 }' ${CLUSTER_ROOT}/${name}/.openshift_install.log)  
**Platform:** ${platform}  
**Requestor:** ${requestor}  
**Email:** ${email}  
**Description:** ${description}  
**Openshift Console:** [https://console-openshift-console.apps.${name}.${OPENSHIFT_BASE_DOMAIN}](https://console-openshift-console.apps.${name}.${OPENSHIFT_BASE_DOMAIN})  
**Openshift Username:** kubeadmin  
**Openshift Password:** [kubeadmin-password](https://github.com/open-cluster-management/demo-env/blob/master/clusters/${OPENSHIFT_BASE_DOMAIN}/${name}/auth/kubeadmin-password)  
**Kubeconfig file:** [kubeconfig](https://github.com/open-cluster-management/demo-env/blob/master/clusters/${OPENSHIFT_BASE_DOMAIN}/${name}/auth/kubeconfig)  
**openshift-install config file:** [install-config.yaml](https://github.com/open-cluster-management/demo-env/blob/master/clusters/${OPENSHIFT_BASE_DOMAIN}/${name}/install-config_aws.yaml)  
**install log:** [.openshift_install.log](https://github.com/open-cluster-management/demo-env/blob/master/clusters/${OPENSHIFT_BASE_DOMAIN}/${name}/.openshift_install.log)  
**Open Cluster Management Console:** [https://multicloud-console.apps.${name}.${OPENSHIFT_BASE_DOMAIN}](https://multicloud-console.apps.${name}.${OPENSHIFT_BASE_DOMAIN})  
**Open Cluster Management Username:** kubeadmin  
**Open Cluster Management Password:** [kubeadmin-password](https://github.com/open-cluster-management/demo-env/blob/master/clusters/${OPENSHIFT_BASE_DOMAIN}/${name}/auth/kubeadmin-password) 
