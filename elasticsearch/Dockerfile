ARG ELK_VERSION

# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch-oss:${ELK_VERSION}

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
ARG ELK_VERSION
RUN elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v${ELK_VERSION}/elasticsearch-analysis-ik-${ELK_VERSION}.zip
