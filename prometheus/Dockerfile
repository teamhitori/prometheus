FROM prom/prometheus
COPY ./prometheus.yml /etc/prometheus/

EXPOSE     8080
WORKDIR    /prometheus
ENTRYPOINT [ "/bin/prometheus", "--config.file=/etc/prometheus/prometheus.yml", "--web.listen-address=:8080" ]