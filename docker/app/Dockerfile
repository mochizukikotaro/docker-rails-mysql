FROM ruby:2.7-buster

RUN apt update -qq

# node
RUN curl -sL https://deb.nodesource.com/setup_12.x | bash - \
    && apt-get install -y nodejs

WORKDIR /myapp
