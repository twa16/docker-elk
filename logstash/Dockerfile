FROM docker.elastic.co/logstash/logstash:5.5.1

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

RUN logstash-plugin install logstash-filter-syslog_pri
RUN logstash-plugin install logstash-input-syslog

