ARG ELK_VERSION
FROM elasticsearch:${ELK_VERSION}

# VOLUME /elasticsearch /elasticsearch/data

COPY elasticsearch_synonyms.txt /usr/share/elasticsearch/config/

EXPOSE 9200 9300
