# CHANGELOG
## 1.1.2 | 2021.01.26
- Fix the error of "Ingress" in v1.18+ cluster
    - Each path in an Ingress is required to have a corresponding path type. Paths that do not include an explicit pathType will fail validation. More info: https://kubernetes.io/docs/concepts/services-networking/ingress/#path-types

## 1.1.0 | 2020.11.11
- Update "Ingress" apiVersion to "networking.k8s.io/v1"

## 1.1.0 | 2020.09.21
- Add "Ingress"
- Add "Ingress(TLS)"
- Remove "IngressRoute(traefik.containo.us/v1alpha1)"
- Rename "Middleware" to "TraefikMiddleware"

## 1.0.10 | 2020.07.08
- Update "Secret、Service、Endpoints、PersistentVolumeClaim、Deployment、StatefulSet、Pod、CronJob"
    - Add ".metadata.namespace"
- Update "Deployment"
    - Fix ".spec.template.spec.containers.resources.*.memory" default value format error.
    - Add ".spec.template.spec.initContainers" comment.
    - Modify ".spec.template.spec.containers.image" default value.

## 1.0.9 | 2020.06.19
- Update "Deployment"
    - Add ".spec.containers.resources"

## 1.0.8 | 2020.06.17
- Fix "Deployment"
    - Remove ".spec.template.spec.imagePullPolicy"
    - Update ".spec.template.matedata.labels", Change the default label 'name' to 'app'.

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