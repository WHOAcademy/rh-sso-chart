# Red Hat SSO Operator Chart

This chart is created to manage Red Hat SSO Operator CRDs. It uses the [OperatorHub Chart](https://github.com/redhat-cop/helm-charts/tree/master/charts/operatorhub) dependency in order to subscribe to the Red Hat SSO operator.

## Package and Push Process

helm package . 

curl -v -f -u admin:admin123 https://nexus-labs-ci-cd.apps.who.emea-2.rht-labs.com/repository/helm-charts/ --upload-file rh-sso-chart-0.0.1.tgz

