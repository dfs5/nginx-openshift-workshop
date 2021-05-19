## Prerequisites
Set BIG-IP login credentials for use with Operator Helm charts.

    apiVersion: v1
    kind: Secret
    metadata:
      name: bigip-login
      namespace: kube-system
    type: kubernetes.io/basic-auth
    stringData:
      username: admin
      password: xxxxx

BIG-IP CIS configuration example: https://github.com/F5Networks/k8s-bigip-ctlr/tree/master/operator

BIG-IP configuration examples with routes: https://github.com/F5Networks/k8s-bigip-ctlr/tree/master/docs/config_examples/openshift/routes

Supported Route cofigurations: https://clouddocs.f5.com/containers/latest/userguide/openshift/#supported-route-configurations
