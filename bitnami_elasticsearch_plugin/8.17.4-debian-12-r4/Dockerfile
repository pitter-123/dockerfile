FROM bitnamilegacy/elasticsearch:8.17.4-debian-12-r4
ARG ELASTICSEARCH_VERSION=8.17.4

RUN /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install  --batch \
    https://release.infinilabs.com/analysis-ik/stable/elasticsearch-analysis-ik-${ELASTICSEARCH_VERSION}.zip \
    https://release.infinilabs.com/analysis-pinyin/stable/elasticsearch-analysis-pinyin-${ELASTICSEARCH_VERSION}.zip