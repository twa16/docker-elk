FROM elasticsearch:5

ENV ES_JAVA_OPTS="-Des.path.conf=/etc/elasticsearch"

#RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install x-pack
#RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install mobz/elasticsearch-head
CMD ["-E", "network.host=0.0.0.0", "-E", "discovery.zen.minimum_master_nodes=1"]
