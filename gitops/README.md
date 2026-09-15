# gitops tasks

## must have now
- [ ] maybe on premises
- [ ] jenkins
	- [ ] plugins
		- [ ] git
	- [ ] webhook for github
- [ ] docker
	- [ ] image based on [pyhton:3-alpine-dev](https://hub.docker.com/hardened-images/catalog/dhi/python/images/python%2Falpine-3.24%2F3.14-dev/sha256-45354012e0480baedfe84c1f0d3d10a692f4f8efd136e03ddd576d3c63a4637d)
- [ ] Kubernetes
	- [ ] Docker build an image to run 
	- [ ] add a frontend group 
	- [ ] add a backend group
	- [ ] add a database group
	- [ ] create NodePort service for the group
	- [ ] create the deployment and put the image on it
	- [ ] one cluster with nameapaces
- [ ] ansible
	- [ ] inventory
	- [ ] ansible config
	- [ ] playbooks
		- [ ] restart the docker container
- [ ] implement SonarQube SAST
- [ ] build an image registery
- [ ] terraform
	- [ ] provision one EC2 instance with K3s
	- [ ] provision one EC2 instance with ansible master node
	- [ ] provision onw EC2 instance with worker node kubernetes
- [ ] prometheus
- [ ] grafana
- [ ] implement Open Policy agent
- [ ] build a MQTT server
## must have later
- [ ] automation for docker files 
## nice to have 
- [ ] forecast data for the sensors
- [ ] make a helm chart for the kubernetes task
- [ ] AgroCD