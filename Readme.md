
-----------------------------
Steps to follow the Prometheus Monitoring
----------------------------

[1] Create Kubernetes CRD which is basically schema definition for Prometheus instance. 

[2] Deploy the Prometheus Operator  [Operator will scrap the metrics from all the kubernetes/nodes/VM and application etc]

[3] Configure the Prometheus Rules 

[4] Configure Service Monitoring

[5] Configure Alertmanager configuration

-----------------------------


GITHUB sources:

Archived: https://github.com/helm/charts/blob/master/stable/prometheus-operator/crds/crd-alertmanager.yaml

Latest  : https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack
