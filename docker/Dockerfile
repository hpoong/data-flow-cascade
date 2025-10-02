

# docker build -t debezium-connect-jdbc-sink:2.4 .

FROM debezium/connect:2.4

# Kafka Connect 플러그인 디렉토리를 지정
ENV KAFKA_CONNECT_PLUGINS_DIR /kafka/connect

COPY debezium-connector-jdbc ${KAFKA_CONNECT_PLUGINS_DIR}/debezium-connector-jdbc

ENV CONNECT_PLUGIN_PATH ${KAFKA_CONNECT_PLUGINS_DIR}