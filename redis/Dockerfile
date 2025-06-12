FROM datadog/agent
RUN apt-get update
RUN rm /etc/datadog-agent/conf.d/redisdb.d/conf.yaml.example
COPY ./redisdb_conf.yaml ./etc/datadog-agent/conf.d/redisdb.d/conf.yaml