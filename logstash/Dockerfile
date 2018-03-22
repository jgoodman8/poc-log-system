FROM logstash

RUN logstash-plugin install logstash-output-influxdb
RUN logstash-plugin install logstash-output-elasticsearch

COPY logstash.conf .

CMD ["-f", "logstash.conf"]


