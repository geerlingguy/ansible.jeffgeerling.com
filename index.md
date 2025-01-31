---
title: ''
description: ''
---
## About Jeff Geerling (geerlingguy)

[Jeff Geerling](https://www.jeffgeerling.com) is an author and software developer from St. Louis, MO. He started using Ansible in 2013 and maintains numerous Ansible works.

## Ansible Books

| <a href="https://www.ansiblefordevops.com/"><img src="assets/images/ansible-for-devops.jpg" alt="Ansible for DevOps" /></a> | <a href="https://www.ansibleforkubernetes.com/"><img src="assets/images/ansible-for-kubernetes.jpg" alt="Ansible for Kubernetes" /></a> |
| :---: | :---: |
| [Ansible for DevOps](https://www.ansiblefordevops.com) | [Ansible for Kubernetes](https://www.ansibleforkubernetes.com) |

## Project Maintenance Status

I maintain over 250 open source projects and two bestselling books, and without some level of automation (and maybe a little sleep from time to time), it would be impossible for me to keep all the projects relevant.

I use a [stale issue bot](https://www.jeffgeerling.com/blog/2020/enabling-stale-issue-bot-on-my-github-repositories) to clean up repository issues and PRs, and I also sometimes informally put a project into 'maintenance only' mode. That is indicated in the listings below using the following conventions:

| Icon | Description |
| ---: | ----------- |
| &#10003; | Actively used and maintained. |
| &#33; | Maintenance and bugfixes only. |
| &#10007; | Not maintained. |

## Table of Contents

  - [Ansible-based Operators](#operators)
  - [Container Images Built with Ansible](#container-images)
  - [Container Images for Ansible Testing](#container-images-testing)
  - [Ansible Collections](#collections)
  - [Ansible Roles](#roles)
  - [Ansible Projects](#projects)
  - [Ansible Videos and Presentations](#presentations)

## <a name="operators"></a>Ansible-based Operators

| Name | Test Status | Maintained? | Repository |
| ---- | ----------- | ----------- | ---------- |
| [Drupal Operator](https://github.com/geerlingguy/drupal-operator) | [![Build Status](https://travis-ci.com/geerlingguy/drupal-operator.svg?branch=master)](https://travis-ci.com/geerlingguy/drupal-operator) | &#10003; | [GitHub](https://github.com/geerlingguy/drupal-operator) |
| [MariaDB Operator](https://github.com/geerlingguy/mariadb-operator) | [![Build Status](https://travis-ci.com/geerlingguy/mariadb-operator.svg?branch=master)](https://travis-ci.com/geerlingguy/mariadb-operator) | &#33; | [GitHub](https://github.com/geerlingguy/mariadb-operator) |
| [Mcrouter Operator](https://github.com/geerlingguy/mcrouter-operator) | [![Build Status](https://travis-ci.com/geerlingguy/mcrouter-operator.svg?branch=master)](https://travis-ci.com/geerlingguy/mcrouter-operator) | &#33; | [GitHub](https://github.com/geerlingguy/mcrouter-operator) |
| [Ansible Tower/AWX Operator](https://github.com/geerlingguy/tower-operator) | [![Build Status](https://travis-ci.com/geerlingguy/tower-operator.svg?branch=master)](https://travis-ci.com/geerlingguy/tower-operator) | &#10007; | [GitHub](https://github.com/geerlingguy/tower-operator) |

<a href="#">Back to Top</a>

## <a name="container-images"></a>Container Images Built with Ansible

| Name | Test Status | Maintained? | Repository |
| ---- | ----------- | ----------- | ---------- |
| [geerlingguy/drupal](https://hub.docker.com/r/geerlingguy/drupal/) | [![Build Status](https://travis-ci.org/geerlingguy/drupal-container.svg?branch=master)](https://travis-ci.org/geerlingguy/drupal-container) | &#10003; | [GitHub](https://github.com/geerlingguy/drupal-container) |
| [geerlingguy/fathom](https://hub.docker.com/r/geerlingguy/fathom/) | [![Build Status](https://travis-ci.org/geerlingguy/fathom-container.svg?branch=master)](https://travis-ci.org/geerlingguy/fathom-container) | &#10003; | [GitHub](https://github.com/geerlingguy/fathom-container) |
| [geerlingguy/php-apache](https://hub.docker.com/r/geerlingguy/php-apache/) | [![Build Status](https://travis-ci.org/geerlingguy/php-apache-container.svg?branch=master)](https://travis-ci.org/geerlingguy/php-apache-container) | &#10003; | [GitHub](https://github.com/geerlingguy/php-apache-container) |
| [geerlingguy/solr](https://hub.docker.com/r/geerlingguy/solr/) | [![Build Status](https://travis-ci.org/geerlingguy/solr-container.svg?branch=master)](https://travis-ci.org/geerlingguy/solr-container) | &#10003; | [GitHub](https://github.com/geerlingguy/solr-container) |

<a href="#">Back to Top</a>

## <a name="container-images-testing"></a>Container Images for Ansible Testing

| Name | Test Status | Maintained? | Repository |
| ---- | ----------- | ----------- | ---------- |
| [geerlingguy/docker-ubuntu2404-ansible](https://hub.docker.com/r/geerlingguy/docker-ubuntu2404-ansible/) | [![Build](https://github.com/geerlingguy/docker-ubuntu2404-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-ubuntu2404-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-ubuntu2404-ansible) |
| [geerlingguy/docker-ubuntu2204-ansible](https://hub.docker.com/r/geerlingguy/docker-ubuntu2204-ansible/) | [![Build](https://github.com/geerlingguy/docker-ubuntu2204-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-ubuntu2204-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-ubuntu2204-ansible) |
| [geerlingguy/docker-ubuntu2004-ansible](https://hub.docker.com/r/geerlingguy/docker-ubuntu2004-ansible/) | [![Build](https://github.com/geerlingguy/docker-ubuntu2004-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-ubuntu2004-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-ubuntu2004-ansible) |
| [geerlingguy/docker-rockylinux9-ansible](https://hub.docker.com/r/geerlingguy/docker-rockylinux9-ansible/) | [![Build](https://github.com/geerlingguy/docker-rockylinux9-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-rockylinux9-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-rockylinux9-ansible) |
| [geerlingguy/docker-rockylinux8-ansible](https://hub.docker.com/r/geerlingguy/docker-rockylinux8-ansible/) | [![Build](https://github.com/geerlingguy/docker-rockylinux8-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-rockylinux8-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-rockylinux8-ansible) |
| [geerlingguy/docker-debian12-ansible](https://hub.docker.com/r/geerlingguy/docker-debian12-ansible/) | [![Build](https://github.com/geerlingguy/docker-debian12-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-debian12-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-debian12-ansible) |
| [geerlingguy/docker-debian11-ansible](https://hub.docker.com/r/geerlingguy/docker-debian11-ansible/) | [![Build](https://github.com/geerlingguy/docker-debian11-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-debian11-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-debian11-ansible) |
| [geerlingguy/docker-amazonlinux2023-ansible](https://hub.docker.com/r/geerlingguy/docker-amazonlinux2023-ansible/) | [![Build](https://github.com/geerlingguy/docker-amazonlinux2023-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-amazonlinux2023-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-amazonlinux2023-ansible) |
| [geerlingguy/docker-fedora41-ansible](https://hub.docker.com/r/geerlingguy/docker-fedora41-ansible/) | [![Build](https://github.com/geerlingguy/docker-fedora41-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-fedora41-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-fedora41-ansible) |
| [geerlingguy/docker-fedora40-ansible](https://hub.docker.com/r/geerlingguy/docker-fedora40-ansible/) | [![Build](https://github.com/geerlingguy/docker-fedora40-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-fedora40-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-fedora40-ansible) |
| [geerlingguy/docker-fedora39-ansible](https://hub.docker.com/r/geerlingguy/docker-fedora39-ansible/) | [![Build](https://github.com/geerlingguy/docker-fedora39-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/geerlingguy/docker-fedora39-ansible/actions/workflows/build.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-fedora39-ansible) |


See also: [Testing your roles with Molecule](https://www.jeffgeerling.com/blog/2018/testing-your-ansible-roles-molecule)

<a href="#">Back to Top</a>

## <a name="collections"></a>Ansible Collections

| Name | Test Status | Maintained? | Repository |
| ---- | ----------- | ----------- | ---------- |
| [geerlingguy.k8s](https://galaxy.ansible.com/geerlingguy/k8s) | N/A | &#10007; | [GitHub](https://github.com/geerlingguy/ansible-collection-k8s) |
| [geerlingguy.mac](https://galaxy.ansible.com/geerlingguy/mac) | [![CI](https://github.com/geerlingguy/ansible-collection-mac/actions/workflows/ci.yml/badge.svg?branch=master&event=push)](https://github.com/geerlingguy/ansible-collection-mac/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-collection-mac) |
| [geerlingguy.php_roles](https://galaxy.ansible.com/geerlingguy/php_roles) | N/A | &#10007; | [GitHub](https://github.com/geerlingguy/ansible-collection-php_roles) |

<a href="#">Back to Top</a>

## <a name="roles"></a>Ansible Roles

| Name | Test Status | Maintained? | Repository |
| ---- | ----------- | ----------- | ---------- |
| [geerlingguy.ansible](https://galaxy.ansible.com/geerlingguy/ansible) | [![CI](https://github.com/geerlingguy/ansible-role-ansible/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-ansible/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-ansible) |
| [geerlingguy.apache](https://galaxy.ansible.com/geerlingguy/apache) | [![CI](https://github.com/geerlingguy/ansible-role-apache/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-apache/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-apache) |
| [geerlingguy.apache-php-fpm](https://galaxy.ansible.com/geerlingguy/apache-php-fpm) | [![CI](https://github.com/geerlingguy/ansible-role-apache-php-fpm/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-apache-php-fpm/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-apache-php-fpm) |
| [geerlingguy.backup](https://galaxy.ansible.com/geerlingguy/backup) | [![CI](https://github.com/geerlingguy/ansible-role-backup/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-backup/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-backup) |
| [geerlingguy.bad_judgement](https://galaxy.ansible.com/geerlingguy/bad_judgement) | [![CI](https://github.com/geerlingguy/ansible-role-bad_judgement/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-bad_judgement/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-bad_judgement) |
| [geerlingguy.certbot](https://galaxy.ansible.com/geerlingguy/certbot) | [![CI](https://github.com/geerlingguy/ansible-role-certbot/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-certbot/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-certbot) |
| [geerlingguy.clamav](https://galaxy.ansible.com/geerlingguy/clamav) | [![CI](https://github.com/geerlingguy/ansible-role-clamav/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-clamav/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-clamav) |
| [geerlingguy.composer](https://galaxy.ansible.com/geerlingguy/composer) | [![CI](https://github.com/geerlingguy/ansible-role-composer/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-composer/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-composer) |
| [geerlingguy.daemonize](https://galaxy.ansible.com/geerlingguy/daemonize) | [![CI](https://github.com/geerlingguy/ansible-role-daemonize/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-daemonize/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-daemonize) |
| [geerlingguy.docker](https://galaxy.ansible.com/geerlingguy/docker) | [![CI](https://github.com/geerlingguy/ansible-role-docker/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-docker/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-docker) |
| [geerlingguy.dotfiles](https://galaxy.ansible.com/geerlingguy/dotfiles) | [![CI](https://github.com/geerlingguy/ansible-role-dotfiles/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-dotfiles/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-dotfiles) |
| [geerlingguy.drupal](https://galaxy.ansible.com/geerlingguy/drupal) | [![CI](https://github.com/geerlingguy/ansible-role-drupal/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-drupal/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-drupal) |
| [geerlingguy.drush](https://galaxy.ansible.com/geerlingguy/drush) | [![CI](https://github.com/geerlingguy/ansible-role-drush/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-drush/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-drush) |
| [geerlingguy.elasticsearch](https://galaxy.ansible.com/geerlingguy/elasticsearch) | [![CI](https://github.com/geerlingguy/ansible-role-elasticsearch/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-elasticsearch/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-elasticsearch) |
| [geerlingguy.elasticsearch-curator](https://galaxy.ansible.com/geerlingguy/elasticsearch-curator) | [![CI](https://github.com/geerlingguy/ansible-role-elasticsearch-curator/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-elasticsearch-curator/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-elasticsearch-curator) |
| [geerlingguy.exim](https://galaxy.ansible.com/geerlingguy/exim) | [![CI](https://github.com/geerlingguy/ansible-role-exim/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-exim/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-exim) |
| [geerlingguy.fathom](https://galaxy.ansible.com/geerlingguy/fathom) | [![CI](https://github.com/geerlingguy/ansible-role-fathom/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-fathom/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-fathom) |
| [geerlingguy.filebeat](https://galaxy.ansible.com/geerlingguy/filebeat) | [![CI](https://github.com/geerlingguy/ansible-role-filebeat/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-filebeat/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-filebeat) |
| [geerlingguy.firewall](https://galaxy.ansible.com/geerlingguy/firewall) | [![CI](https://github.com/geerlingguy/ansible-role-firewall/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-firewall/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-firewall) |
| [geerlingguy.git](https://galaxy.ansible.com/geerlingguy/git) | [![CI](https://github.com/geerlingguy/ansible-role-git/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-git/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-git) |
| [geerlingguy.github-users](https://galaxy.ansible.com/geerlingguy/github-users) | [![CI](https://github.com/geerlingguy/ansible-role-github-users/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-github-users/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-github-users) |
| [geerlingguy.haproxy](https://galaxy.ansible.com/geerlingguy/haproxy) | [![CI](https://github.com/geerlingguy/ansible-role-haproxy/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-haproxy/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-haproxy) |
| [geerlingguy.hdparm](https://galaxy.ansible.com/geerlingguy/hdparm) | [![CI](https://github.com/geerlingguy/ansible-role-hdparm/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-hdparm/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-hdparm) |
| [geerlingguy.helm](https://galaxy.ansible.com/geerlingguy/helm) | [![CI](https://github.com/geerlingguy/ansible-role-helm/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-helm/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-helm) |
| [geerlingguy.htpasswd](https://galaxy.ansible.com/geerlingguy/htpasswd) | [![CI](https://github.com/geerlingguy/ansible-role-htpasswd/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-htpasswd/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-htpasswd) |
| [geerlingguy.java](https://galaxy.ansible.com/geerlingguy/java) | [![CI](https://github.com/geerlingguy/ansible-role-java/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-java/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-java) |
| [geerlingguy.jenkins](https://galaxy.ansible.com/geerlingguy/jenkins) | [![CI](https://github.com/geerlingguy/ansible-role-jenkins/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-jenkins/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-jenkins) |
| [geerlingguy.k8s_manifests](https://galaxy.ansible.com/geerlingguy/k8s_manifests) | [![CI](https://github.com/geerlingguy/ansible-role-k8s_manifests/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-k8s_manifests/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-k8s_manifests) |
| [geerlingguy.kibana](https://galaxy.ansible.com/geerlingguy/kibana) | [![CI](https://github.com/geerlingguy/ansible-role-kibana/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-kibana/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-kibana) |
| [geerlingguy.kubernetes](https://galaxy.ansible.com/geerlingguy/kubernetes) | [![CI](https://github.com/geerlingguy/ansible-role-kubernetes/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-kubernetes/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-kubernetes) |
| [geerlingguy.logstash](https://galaxy.ansible.com/geerlingguy/logstash) | [![CI](https://github.com/geerlingguy/ansible-role-logstash/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-logstash/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-logstash) |
| [geerlingguy.mailhog](https://galaxy.ansible.com/geerlingguy/mailhog) | [![CI](https://github.com/geerlingguy/ansible-role-mailhog/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-mailhog/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-mailhog) |
| [geerlingguy.memcached](https://galaxy.ansible.com/geerlingguy/memcached) | [![CI](https://github.com/geerlingguy/ansible-role-memcached/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-memcached/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-memcached) |
| [geerlingguy.munin](https://galaxy.ansible.com/geerlingguy/munin) | [![CI](https://github.com/geerlingguy/ansible-role-munin/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-munin/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-munin) |
| [geerlingguy.munin-node](https://galaxy.ansible.com/geerlingguy/munin-node) | [![CI](https://github.com/geerlingguy/ansible-role-munin-node/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-munin-node/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-munin-node) |
| [geerlingguy.mysql](https://galaxy.ansible.com/geerlingguy/mysql) | [![CI](https://github.com/geerlingguy/ansible-role-mysql/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-mysql/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-mysql) |
| [geerlingguy.nfs](https://galaxy.ansible.com/geerlingguy/nfs) | [![CI](https://github.com/geerlingguy/ansible-role-nfs/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-nfs/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-nfs) |
| [geerlingguy.nginx](https://galaxy.ansible.com/geerlingguy/nginx) | [![CI](https://github.com/geerlingguy/ansible-role-nginx/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-nginx/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-nginx) |
| [geerlingguy.nodejs](https://galaxy.ansible.com/geerlingguy/nodejs) | [![CI](https://github.com/geerlingguy/ansible-role-nodejs/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-nodejs/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-nodejs) |
| [geerlingguy.ntp](https://galaxy.ansible.com/geerlingguy/ntp) | [![CI](https://github.com/geerlingguy/ansible-role-ntp/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-ntp/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-ntp) |
| [geerlingguy.packer](https://galaxy.ansible.com/geerlingguy/packer) | [![CI](https://github.com/geerlingguy/ansible-role-packer/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-packer/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-packer) |
| [geerlingguy.packer-debian](https://galaxy.ansible.com/geerlingguy/packer-debian) | [![CI](https://github.com/geerlingguy/ansible-role-packer-debian/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-packer-debian/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-packer-debian) |
| [geerlingguy.packer_rhel](https://galaxy.ansible.com/geerlingguy/packer_rhel) | [![CI](https://github.com/geerlingguy/ansible-role-packer_rhel/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-packer_rhel/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-packer_rhel) |
| [geerlingguy.passenger](https://galaxy.ansible.com/geerlingguy/passenger) | [![CI](https://github.com/geerlingguy/ansible-role-passenger/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-passenger/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-passenger) |
| [geerlingguy.php](https://galaxy.ansible.com/geerlingguy/php) | [![CI](https://github.com/geerlingguy/ansible-role-php/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php) |
| [geerlingguy.php-memcached](https://galaxy.ansible.com/geerlingguy/php-memcached) | [![CI](https://github.com/geerlingguy/ansible-role-php-memcached/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php-memcached/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-memcached) |
| [geerlingguy.php-mysql](https://galaxy.ansible.com/geerlingguy/php-mysql) | [![CI](https://github.com/geerlingguy/ansible-role-php-mysql/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php-mysql/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-mysql) |
| [geerlingguy.php-pear](https://galaxy.ansible.com/geerlingguy/php-pear) | [![CI](https://github.com/geerlingguy/ansible-role-php-pear/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php-pear/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-pear) |
| [geerlingguy.php-pecl](https://galaxy.ansible.com/geerlingguy/php-pecl) | [![CI](https://github.com/geerlingguy/ansible-role-php-pecl/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php-pecl/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-pecl) |
| [geerlingguy.php-pgsql](https://galaxy.ansible.com/geerlingguy/php-pgsql) | [![CI](https://github.com/geerlingguy/ansible-role-php-pgsql/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php-pgsql/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-pgsql) |
| [geerlingguy.php-redis](https://galaxy.ansible.com/geerlingguy/php-redis) | [![CI](https://github.com/geerlingguy/ansible-role-php-redis/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php-redis/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-redis) |
| [geerlingguy.php-versions](https://galaxy.ansible.com/geerlingguy/php-versions) | [![CI](https://github.com/geerlingguy/ansible-role-php-versions/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php-versions/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-versions) |
| [geerlingguy.php-xdebug](https://galaxy.ansible.com/geerlingguy/php-xdebug) | [![CI](https://github.com/geerlingguy/ansible-role-php-xdebug/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php-xdebug/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-xdebug) |
| [geerlingguy.php-xhprof](https://galaxy.ansible.com/geerlingguy/php-xhprof) | [![CI](https://github.com/geerlingguy/ansible-role-php-xhprof/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-php-xhprof/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-xhprof) |
| [geerlingguy.pip](https://galaxy.ansible.com/geerlingguy/pip) | [![CI](https://github.com/geerlingguy/ansible-role-pip/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-pip/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-pip) |
| [geerlingguy.postfix](https://galaxy.ansible.com/geerlingguy/postfix) | [![CI](https://github.com/geerlingguy/ansible-role-postfix/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-postfix/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-postfix) |
| [geerlingguy.postgresql](https://galaxy.ansible.com/geerlingguy/postgresql) | [![CI](https://github.com/geerlingguy/ansible-role-postgresql/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-postgresql/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-postgresql) |
| [geerlingguy.puppet](https://galaxy.ansible.com/geerlingguy/puppet) | [![CI](https://github.com/geerlingguy/ansible-role-puppet/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-puppet/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-puppet) |
| [geerlingguy.rabbitmq](https://galaxy.ansible.com/geerlingguy/rabbitmq) | [![CI](https://github.com/geerlingguy/ansible-role-rabbitmq/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-rabbitmq/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-rabbitmq) |
| [geerlingguy.raspberry-pi](https://galaxy.ansible.com/geerlingguy/raspberry-pi) | [![CI](https://github.com/geerlingguy/ansible-role-raspberry-pi/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-raspberry-pi/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-raspberry-pi) |
| [geerlingguy.redis](https://galaxy.ansible.com/geerlingguy/redis) | [![CI](https://github.com/geerlingguy/ansible-role-redis/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-redis/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-redis) |
| [geerlingguy.repo-epel](https://galaxy.ansible.com/geerlingguy/repo-epel) | [![CI](https://github.com/geerlingguy/ansible-role-repo-epel/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-repo-epel/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-repo-epel) |
| [geerlingguy.repo-remi](https://galaxy.ansible.com/geerlingguy/repo-remi) | [![CI](https://github.com/geerlingguy/ansible-role-repo-remi/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-repo-remi/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-repo-remi) |
| [geerlingguy.ruby](https://galaxy.ansible.com/geerlingguy/ruby) | [![CI](https://github.com/geerlingguy/ansible-role-ruby/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-ruby/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-ruby) |
| [geerlingguy.samba](https://galaxy.ansible.com/geerlingguy/samba) | [![CI](https://github.com/geerlingguy/ansible-role-samba/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-samba/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-samba) |
| [geerlingguy.security](https://galaxy.ansible.com/geerlingguy/security) | [![CI](https://github.com/geerlingguy/ansible-role-security/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-security/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-security) |
| [geerlingguy.solr](https://galaxy.ansible.com/geerlingguy/solr) | [![CI](https://github.com/geerlingguy/ansible-role-solr/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-solr/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-solr) |
| [geerlingguy.ssh-chroot-jail](https://galaxy.ansible.com/geerlingguy/ssh-chroot-jail) | [![CI](https://github.com/geerlingguy/ansible-role-ssh-chroot-jail/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-ssh-chroot-jail/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-ssh-chroot-jail) |
| [geerlingguy.supervisor](https://galaxy.ansible.com/geerlingguy/supervisor) | [![CI](https://github.com/geerlingguy/ansible-role-supervisor/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-supervisor/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-supervisor) |
| [geerlingguy.svn](https://galaxy.ansible.com/geerlingguy/svn) | [![CI](https://github.com/geerlingguy/ansible-role-svn/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-svn/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-svn) |
| [geerlingguy.svn2git](https://galaxy.ansible.com/geerlingguy/svn2git) | [![CI](https://github.com/geerlingguy/ansible-role-svn2git/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-svn2git/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-svn2git) |
| [geerlingguy.swap](https://galaxy.ansible.com/geerlingguy/swap) | [![CI](https://github.com/geerlingguy/ansible-role-swap/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-swap/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-swap) |
| [geerlingguy.varnish](https://galaxy.ansible.com/geerlingguy/varnish) | [![CI](https://github.com/geerlingguy/ansible-role-varnish/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/ansible-role-varnish/actions/workflows/ci.yml) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-varnish) |


<a href="#">Back to Top</a>

## <a name="projects"></a>Ansible Projects

| Name and Link | Test Status | Maintained? |
| ------------- | ----------- | ----------- |
| [Ansible Requirements Updater](https://github.com/geerlingguy/ansible-requirements-updater) | N/A | &#10003; |
| [Mac Development Playbook](https://github.com/geerlingguy/mac-dev-playbook) | [![CI](https://github.com/geerlingguy/mac-dev-playbook/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/geerlingguy/mac-dev-playbook/actions/workflows/ci.yml) | &#10003; |
| [Packer Boxes](https://github.com/geerlingguy/packer-boxes) | ![Validate Packer JSON files](https://github.com/geerlingguy/packer-boxes/workflows/Validate%20Packer%20JSON%20files/badge.svg) | &#10003; |
| [Drupal VM](https://www.drupalvm.com) | N/A | &#10007; |
| [Raspberry Pi Dramble](https://www.pidramble.com) | N/A | &#10007; |
| [Drupal Pi](https://github.com/geerlingguy/drupal-pi) | [![CI](https://github.com/geerlingguy/drupal-pi/actions/workflows/CI.yml/badge.svg)](https://github.com/geerlingguy/drupal-pi/actions/workflows/CI.yml) | &#10003; |
| [Pi Cluster](https://github.com/geerlingguy/pi-cluster) | [![CI](https://github.com/geerlingguy/pi-cluster/actions/workflows/ci.yml/badge.svg)](https://github.com/geerlingguy/pi-cluster/actions/workflows/ci.yml) | &#10003; |
| [Ansible Vagrant Examples](https://github.com/geerlingguy/ansible-vagrant-examples) | N/A | &#33; |

Also see [all my blog posts about Ansible](https://www.jeffgeerling.com/category/ansible) and [all my YouTube videos about Ansible](https://www.youtube.com/playlist?list=PL2_OBreMn7FplshFCWYlaN2uS8et9RjNG).

<a href="#">Back to Top</a>

## <a name="presentations"></a>Ansible Videos and Presentations

| Place and Date | Title |
| -------------- | ----- |
| YouTube<br><span class="date">April 2020</span> | [Ansible 101 streaming series](https://www.jeffgeerling.com/blog/2020/ansible-101-jeff-geerling-youtube-streaming-series) |
| DrupalCon Seattle 2019<br><span class="date">November 26, 2019</span> | [Everything I know about Kubernetes I learned from a cluster of Raspberry Pis](https://www.jeffgeerling.com/blog/2019/everything-i-know-about-kubernetes-i-learned-cluster-raspberry-pis) |
| AnsibleFest Atlanta 2019<br><span class="date">September 25, 2019</span> | [There's a Role for that! How to evaluate community roles for your playbook](https://www.jeffgeerling.com/blog/2019/how-evaluate-community-ansible-roles-your-playbooks) |
| AnsibleFest Austin 2018<br><span class="date">August 21, 2018</span> | [Make your Ansible playbooks flexible, maintainable, and scalable](https://www.youtube.com/watch?v=kNDL13MJG6Y) |
| MidCamp 2018<br><span class="date">March 10, 2018</span> | [Jenkins or: How I learned to stop worrying and love automation](https://www.midcamp.org/2018/topic-proposal/jenkins-or-how-i-learned-stop-worrying-and-love-automation) |
| AnsibleFest SF 2016<br><span class="date">July 28, 2016</span> | [Ansible Roles for Fun and Profit!](https://www.ansible.com/ansible-roles-by-acquia) |
| php[tek] 2016<br><span class="date">May 25, 2016</span> | [Highly Available Drupal on a Raspberry Pi Cluster](https://www.jeffgeerling.com/blog/2016/highly-available-drupal-on-raspberry-pi-cluster-phptek-2016-session) |
| YouTube<br><span class="date">July 27, 2015</span> | [Nginx Load Balancer Visualization on a Cluster of Raspberry Pis](https://www.youtube.com/watch?v=7Tf2f5gdO4I) |
| YouTube<br><span class="date">July 14, 2015</span> | [Ansible 101 on a Cluster of Raspberry Pi 2s](https://www.youtube.com/watch?v=ZNB1at8mJWY) |
| MidCamp 2015<br><span class="date">March 21, 2015</span> | [Ansible + Drupal: A Fortuitous DevOps Match](https://www.jeffgeerling.com/blog/midcamp-2015-ansible-drupal-8-presentation) |
| YouTube<br><span class="date">March 8, 2015</span> | [Ansible serial/forks demo on a Cluster of Raspberry Pis](https://www.youtube.com/watch?v=rRJQiHydVG4) |
| DrupalCon Austin<br><span class="date">June 5, 2014</span> | [DevOps for Humans: Ansible for Drupal Deployment Victory!](https://www.jeffgeerling.com/blog/devops-humans-ansible-presentation-drupalcon)
| Meetup<br><span class="date">January 14, 2014</span> | [Local Dev on Virtual Machines - Vagrant, VirtualBox and Ansible](https://www.jeffgeerling.com/blog/virtualbox-vagrant-and-ansible-local-development) |

<a href="#">Back to Top</a>

## Inspiration

This site was inspired by [Robert de Bock's similar Ansible roles site](https://robertdebock.nl).
