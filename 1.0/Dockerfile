# VERSION 0.1.0
# AUTHOR:         Nicolas Lamirault <nicolas.lamirault@gmail.com>
# DESCRIPTION:    zeiot/rpi-prometheus

FROM resin/armv7hf-debian:jessie
MAINTAINER Nicolas Lamirault <nicolas.lamirault@gmail.com>

ENV PIHOLE_EXPORTER_VERSION 0.1.0

ADD https://bintray.com/artifact/download/nlamirault/oss/pihole_exporter-0.1.0_linux_arm /pihole_exporter
RUN chmod +x /pihole_exporter

EXPOSE     9311

ENTRYPOINT [ "/pihole_exporter" ]
