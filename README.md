# Welcome to Zammad

Zammad is a web based open source helpdesk/ticket system with many features
to manage customer communication via several channels like telephone, facebook,
twitter, chat and e-mails. It is distributed under the GNU AFFERO General Public
 License (AGPL) and tested on Linux, Solaris, AIX, FreeBSD, OpenBSD and Mac OS
10.x. Do you receive many e-mails and want to answer them with a team of agents?
You're going to love Zammad!

## What is zammad-docker-compose repo for?

This repo is meant to be the starting point for somebody who likes to test zammad.
If you like to run zammad in production you should use one of the DEB or RPM packages.

## Getting started with zammad-docker-compose

* git clone git@github.com:monotek/zammad-docker-compose.git
* cd zammad-docker-compose

### Setting vm.max_map_count for Elasticsearch

* sysctl -w vm.max_map_count=262144

### Using DockerHub images

* docker-compose up

### Building locally

* docker-compose -f docker-compose-build.yml up

## Docs

https://docs.zammad.org/en/latest/contributing-install-docker.html
