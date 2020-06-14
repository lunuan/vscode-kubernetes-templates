# kubernetes-templates

Are you still worried about how to create kubernetes resources? Are you still worried that the resources you created do not meet the requirements?
Let me help you, kubernetes-templates can help you quickly generate YAML files that define kubernetes resources.

## Getting Started
- Create a YAML file, enter k8s
- Select the resource object you want to create from the pop-up list

![avatar](https://raw.githubusercontent.com/lunuan/vscode-kubernetes-templates/master/static/demo.png)

## Features
- This extension only provides automatic completion when creating resource objects.
- Please rest assured to use.
- Simplicity is the most powerful.


## Requirements
- Visual Studio Code >= 1.38
- Kubernetes >= 1.15.6
- Traefik of Kubernetes (if you want to use it)

## Known Issues
- "Deployment.spec.template.spec.ports" default value format error

## Release Notes

### 1.0.7
- Update "ConfigMap"
    - add ".metadata.name" default value
    - add ".data" examples
- Update "Pod"
    - Modify ".metadata.labels" examples
    - Add ".spec.containers.resources"
    - Add ".spec.containers.env"
    - Add ".spec.containers.ports"
    - Add ".spec.containers.volumeMounts"
    - Add ".spec.volumes"

### 1.0.6
- Fix "PersistentVolumeClaim.spec.accessModes" default type.
    - AccessModes contains the desired access modes the volume should have. More info: https://kubernetes.io/docs/concepts/storage/persistent-volumes#access-modes-1
    - Incorrect type. Expected "array".

### 1.0.5
- Fix "Deployment.spec.template.spec.ports" default value format error

### 1.0.0
- Add commonly used kubernetes objects
    - ConfigMap
    - Secret
    - Service
    - Endpoints
    - PersistentVolumeClaim
    - Deployment
    - DaemonSet
    - StatefulSet
    - Pod
    - Job
    - CronJob
    - Traefik IngressRoute
    - Traefik Middleware

-----------------------------------------------------------------------------------------------------------

**Enjoy!**
