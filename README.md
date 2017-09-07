# Weblogic ELK

Filebeat and Logstash for Weblogic

- Download and install Filebeat, Logstash and ElasticSearch
- Install the plugin logstash-filter-translate
	> logstash-plugin install logstash-filter-translate
- Start ElasticSearch
- Start FileBeat
	> filebeat -c weblogic-filebeat.yml
- Start Logstash
	> logstash -f weblogic-logstash-pipeline.conf --config.reload.automatic

To see all details go to http://carlgira.blogspot.com.es/2017/09/logstash-configuration-for-weblogic.html