
FROM docker.elastic.co/elasticsearch/elasticsearch:9.2.0

ENV discovery.type=single-node
ENV xpack.security.enabled=false
ENV ES_JAVA_OPTS="-Xms512m -Xmx512m"
ENV http.host=0.0.0.0
ENV transport.host=127.0.0.1

EXPOSE 9200
