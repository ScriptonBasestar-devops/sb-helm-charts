# Helm Chart - ScriptonBasestar

k3s 설정시 필요한것들

## 용도별

### Network
- openldap
- squid

### Data
- mariadb
- redis
- postgresql
- memcached
- mongodb
- cassandra

### K3s
- coredns
- cert-manager
- traefik
- istio

### Message
- rabbitmq
- kafka
- zookeeper

### DevOps
- argo-cd

### Etc
- nextcloud
- keycloak
- consul
- vault

## 외

차트없는것들
그리고 kafka처럼 zookeepr와 너무 합쳐져있는것들
때문에 시작했지만
helm차트는 용도에 따라 따로 만들어야 한다는 것
