# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:7.5.2
# Add your logstash plugins setup here
RUN logstash-plugin install logstash-input-beats
RUN logstash-plugin install logstash-input-jdbc
RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-geoip
