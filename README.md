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
- "PersistentVolumeClaim.spec.accessModes" Incorrect type. Expected "array".
- "Deployment.spec.template.spec.ports" default value format error

## Release Notes
[CHANGELOG.MD](https://raw.githubusercontent.com/lunuan/vscode-kubernetes-templates/master/CHANGELOG.md)

-----------------------------------------------------------------------------------------------------------

**Enjoy!**
