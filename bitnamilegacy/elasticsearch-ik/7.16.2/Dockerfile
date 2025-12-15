FROM bitnamilegacy/elasticsearch:7.16.2
ARG ELASTICSEARCH_VERSION=7.16.2

RUN /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install  --batch \
    https://release.infinilabs.com/analysis-ik/stable/elasticsearch-analysis-ik-${ELASTICSEARCH_VERSION}.zip \
    https://release.infinilabs.com/analysis-pinyin/stable/elasticsearch-analysis-pinyin-${ELASTICSEARCH_VERSION}.zip