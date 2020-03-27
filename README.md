# kubernetes-and-ansible
 For centos consult: https://github.com/learnitguide/kubernetes-and-ansible<br/>
 For ubuntu: modify inventory.yml, run the playbook with this command on a different node as master and workers <br/>
 ansible-playbook playbook.yml -i inventory.yml<br/>

 Run this command to deploy a pod network which is needed
 sudo kubectl apply -f https://raw.githubusercontent.com/coreos/flannel/master/Documentation/kube-flannel.yml"

 Now you can deploy kubernetes software
