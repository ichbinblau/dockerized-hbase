ARG VERSION=1.4.13
FROM xshan1/hbase-base:$VERSION

LABEL maintainer="cgiraldo@gradiant.org"
LABEL organization="gradiant.org"

COPY run.sh /run.sh

ENV HBASE_CONF_hbase_master_info_port=60010

EXPOSE 16000 16010
EXPOSE 60010

CMD ["/run.sh"]
