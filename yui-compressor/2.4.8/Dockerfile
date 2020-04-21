FROM        ubuntu:bionic

ENV LANG=en_US.UTF-8
ENV LANGUAGE=en_US:en
ENV LC_ALL=en_US.UTF-8

RUN apt-get update \
    && apt-get install locales yui-compressor -y \
    && echo "en_US UTF-8" > /etc/locale.gen \
    && locale-gen en_US.UTF-8 \

    && apt-get clean \
    && apt-get autoremove