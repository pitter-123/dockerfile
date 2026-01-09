FROM bitnamilegacy/elasticsearch:7.17.16-debian-11-r3
ARG ELASTICSEARCH_VERSION=7.17.16

RUN /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install  --batch \
    https://release.infinilabs.com/analysis-ik/stable/elasticsearch-analysis-ik-${ELASTICSEARCH_VERSION}.zip \
    https://release.infinilabs.com/analysis-pinyin/stable/elasticsearch-analysis-pinyin-${ELASTICSEARCH_VERSION}.zip