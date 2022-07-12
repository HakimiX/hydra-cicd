# Hydra CI/CD

Continuous integration, continuous delivery, and continuous deployment.

Automation and continuous monitoring throughout the lifecycle of apps, from integration and testing phases to delivery and deployment.

**Technologies**: Jenkins _(jdk11)_, Docker, Kubernetes, Python, and Bash. 

* [Overview](#overview)
* [Docker Desktop]
* [Sources](#sources)

## Overview
![](resources/images/hydra-cicd-overview.png)

### Docker Desktop 
Context and namespace
```shell
# Use docker context 
docker context use docker-hydra-cicd

# Use kubernetes context and namespace
kubectx docker-hydra-cicd
kubens docker-hydra-cicd

# Server running on service port
http://localhost:30176/ 
```


### Sources
* [jenkins-docker-desktop](https://github.com/HakimiX/jenkins-docker-desktop)
