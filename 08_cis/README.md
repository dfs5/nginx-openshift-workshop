## Prerequisites
Set BIG-IP login credentials for use with Operator Helm charts.

    vi bigip-login.yaml

    apiVersion: v1
    kind: Secret
    metadata:
      name: bigip-login
      namespace: kube-system
    type: kubernetes.io/basic-auth
    stringData:
      username: admin
      password: xxxxx
