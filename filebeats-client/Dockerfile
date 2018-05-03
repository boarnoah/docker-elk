FROM docker.elastic.co/beats/filebeat:6.2.4

COPY ./logs/ /var/log/nginx/
COPY ./config/filebeat.yml /usr/share/filebeat/filebeat.yml