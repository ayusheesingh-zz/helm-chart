# helm-chart
`$ helm repo add open-telemetry https://ayusheesingh.github.io/helm-chart/` <br>
`$ helm upgrade --install azmon-containers-release-1-ot --set omsagent.instrumentationKey=<your_instrumentation_key>,omsagent.secret.wsid=<your_wsid>,omsagent.secret.key=<your_key>,omsagent.env.clusterName=<your_cluster_name>  open-telemetry/azuremonitor-containers`
