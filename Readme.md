
Links to help during setup:
--------------------------

Ansible k8s setup:
https://www.linuxsysadmins.com/install-kubernetes-cluster-with-ansible/

https://www.youtube.com/watch?v=B9_lUtCueKU



Setting static IP:
https://circuitcloud.in/setup-static-ip-on-virtualbox-ubuntu-server/


Enable Root Login via SSH In Ubuntu:
https://www.liquidweb.com/kb/enable-root-login-via-ssh/


Network solution:
Weave - https://cloud.weave.works/k8s/net
RABL - https://docs.projectcalico.org/v3.3/getting-started/kubernetes/installation/hosted/rbac-kdd.yaml

https://stackoverflow.com/questions/72504257/i-encountered-when-executing-kubeadm-init-error-issue



Before running - cluster-init.yaml
Open the im /etc/containerd/config.toml file
and comment out disabled_plugins = ["cri"]

