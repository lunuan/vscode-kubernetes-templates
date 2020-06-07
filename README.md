# kubernetes-templates

Are you still worried about how to create kubernetes resources? Are you still worried that the resources you created do not meet the requirements?
Let me help you, kubernetes-templates can help you quickly generate YAML files that define kubernetes resources.

How to use this extension?
- Create a YAML file, enter k8s, you will see a list of commonly used kubernetes resources, select the resource object you want to create

![avatar](https://dev.azure.com/lunuan/3c4f5318-ec74-49a3-a8c8-0d62fe17fa79/_apis/git/repositories/b104ca6b-2b03-449c-9df7-5bd10576c3aa/items?path=%2Fstatic%2Fdemo.png&versionDescriptor%5BversionOptions%5D=0&versionDescriptor%5BversionType%5D=0&versionDescriptor%5Bversion%5D=master&resolveLfs=true&%24format=octetStream&api-version=5.0)

## Requirements
- Kubernetes >= 1.15.6
- Visual Studio Code >= 1.38

## Known Issues
- No Issues found, welcome

## Release Notes

### 1.0.4
-  Modify Deployment.spec.template.spec.ports default value format error

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

### 0.0.1
- Initial release of ...

-----------------------------------------------------------------------------------------------------------

**Enjoy!**
