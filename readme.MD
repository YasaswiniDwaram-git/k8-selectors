Taint - to tainte nodes , so that kub-schedular will not consider that node for pod allocation

kubectl taint nodes ip-192-168-10-84.ec2.internal harware=gpu:NoSchedule

UnTaint - to remove taint on nodes

kubectl taint nodes ip-192-168-10-84.ec2.internal harware=gpu:NoSchedule-

Tolerations is added as a exception for taint to schedule a pod inside a node