# Make sure RUBY_VERSION matches the Ruby version in .ruby-version
ARG RUBY_VERSION=3.3.5
FROM ghcr.io/rails/devcontainer/images/ruby:$RUBY_VERSION

USER root
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get install -y redis-tools

USER vscode
