# gitops tasks

## must have now
- [ ] maybe on premises
- [ ] jenkins
	- [ ] plugins
		- [ ] git
	- [ ] webhook for github
    - [ ] pipeline for main branch
    - [ ] build Dockerfile
    - [ ] make sure no keys leaked
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
- [ ] prometheus
    - [ ] scrape k3s metrics
- [ ] grafana
    - [ ] CPU dashboard
    - [ ] live sensor data
- [ ] implement Open Policy agent
- [ ] build a MQTT server
## must have later
- [ ] automation for docker files 
## nice to have 
- [ ] forecast data for the sensors
- [ ] make a helm chart for the kubernetes task
- [ ] AgroCD
- [ ] build an image registery