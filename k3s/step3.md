Workloads can be scheduled via the CLI.

`k create deployment http2 --image=katacoda/docker-http-server`{{execute T2}}

`k get pods`{{execute T2}}

The pods are run via containerd meaning `docker ps`{{execute}} is smpty. However, the processes are running `ps aux | grep app`{{execute}}