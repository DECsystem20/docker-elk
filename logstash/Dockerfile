ARG ELK_VERSION

# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:${ELK_VERSION}

EXPOSE 5000
EXPOSE 5001
EXPOSE 5001/udp

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
