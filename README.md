# openshift-410-patch-dev

helm upgrade --install newrelic-bundle nri-bundle \
--set global.licenseKey=XXXNRAL \
--set global.cluster=YOUCLUSTERNAME \
--namespace=pl \
--set newrelic-pixie.apiKey=px-api-XXXXX \
--set pixie-chart.deployKey=px-dep-XXXX \
--set pixie-chart.clusterName=YOUCLUSTERNAME \
--create-namespace 
