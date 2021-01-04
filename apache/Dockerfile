# =============================================================================
# cetres/centos-apache-php
#
# CentOS-7, Apache 2.4, PHP 7.2
#
# =============================================================================
FROM centos:centos7
LABEL maintainer="Gustavo Oliveira <cetres@gmail.com>"

RUN     yum -y install \
        epel-release \
        httpd \
        php \
        php-mysqli

EXPOSE 80

# -----------------------------------------------------------------------------
# Start
# -----------------------------------------------------------------------------
CMD ["/usr/sbin/httpd", "-DFOREGROUND"]
