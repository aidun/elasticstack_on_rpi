helm install elasticsearch elastic/elasticsearch -f elasticsearch.yml
helm install apm-server elastic/apm-server
helm install filebeat elastic/filebeat
helm install kibana elastic/kibana -f kibana.yml
helm install metricbeat elastic/metricbeat