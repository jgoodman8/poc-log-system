FROM logstash

RUN logstash-plugin install logstash-output-influxdb
RUN logstash-plugin install logstash-output-elasticsearch
RUN logstash-plugin install logstash-output-mongodb

COPY logstash.conf .

CMD ["-f", "logstash.conf"]


