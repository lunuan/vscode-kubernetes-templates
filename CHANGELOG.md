# CHANGELOG

## 1.0.8 | 2020.06.17
- Fix "Deployment"
    - Remove ".spec.template.spec.imagePullPolicy"
    - Update ".spec.template.matedata.labels", Change the default label `name` to `app`

## 1.0.7 | 2020.06.14
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

## 1.0.6 | 2020.06.13
- Fix "PersistentVolumeClaim.spec.accessModes" type.
    - AccessModes contains the desired access modes the volume should have. More info: https://kubernetes.io/docs/concepts/storage/persistent-volumes#access-modes-1

## 1.0.5 | 2020.06.07
- Fix "Deployment.spec.template.spec.ports" default value format error

## 1.0.0 | 2020.06.06
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