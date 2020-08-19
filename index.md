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
| [MariaDB Operator](https://github.com/geerlingguy/mariadb-operator) | [![Build Status](https://travis-ci.com/geerlingguy/mariadb-operator.svg?branch=master)](https://travis-ci.com/geerlingguy/mariadb-operator) | &#10003; | [GitHub](https://github.com/geerlingguy/mariadb-operator) |
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
| [geerlingguy/docker-ubuntu2004-ansible](https://hub.docker.com/r/geerlingguy/docker-ubuntu2004-ansible/) | [![Build Status](https://travis-ci.com/geerlingguy/docker-ubuntu2004-ansible.svg?branch=master)](https://travis-ci.com/geerlingguy/docker-ubuntu2004-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-ubuntu2004-ansible) |
| [geerlingguy/docker-ubuntu1804-ansible](https://hub.docker.com/r/geerlingguy/docker-ubuntu1804-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-ubuntu1804-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-ubuntu1804-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-ubuntu1804-ansible) |
| [geerlingguy/docker-ubuntu1604-ansible](https://hub.docker.com/r/geerlingguy/docker-ubuntu1604-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-ubuntu1604-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-ubuntu1604-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-ubuntu1604-ansible) |
| [geerlingguy/docker-ubuntu1404-ansible](https://hub.docker.com/r/geerlingguy/docker-ubuntu1404-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-ubuntu1404-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-ubuntu1404-ansible) | &#10007; | [GitHub](https://github.com/geerlingguy/docker-ubuntu1404-ansible) |
| [geerlingguy/docker-ubuntu1204-ansible](https://hub.docker.com/r/geerlingguy/docker-ubuntu1204-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-ubuntu1204-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-ubuntu1204-ansible) | &#10007; | [GitHub](https://github.com/geerlingguy/docker-ubuntu1204-ansible) |
| [geerlingguy/docker-centos8-ansible](https://hub.docker.com/r/geerlingguy/docker-centos8-ansible/) | [![Build Status](https://travis-ci.com/geerlingguy/docker-centos8-ansible.svg?branch=master)](https://travis-ci.com/geerlingguy/docker-centos8-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-centos8-ansible) |
| [geerlingguy/docker-centos7-ansible](https://hub.docker.com/r/geerlingguy/docker-centos7-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-centos7-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-centos7-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-centos7-ansible) |
| [geerlingguy/docker-centos6-ansible](https://hub.docker.com/r/geerlingguy/docker-centos6-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-centos6-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-centos6-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-centos6-ansible) |
| [geerlingguy/docker-debian10-ansible](https://hub.docker.com/r/geerlingguy/docker-debian10-ansible/) | [![Build Status](https://travis-ci.com/geerlingguy/docker-debian10-ansible.svg?branch=master)](https://travis-ci.com/geerlingguy/docker-debian10-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-debian10-ansible) |
| [geerlingguy/docker-debian9-ansible](https://hub.docker.com/r/geerlingguy/docker-debian9-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-debian9-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-debian9-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-debian9-ansible) |
| [geerlingguy/docker-debian8-ansible](https://hub.docker.com/r/geerlingguy/docker-debian8-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-debian8-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-debian8-ansible) | &#10007; | [GitHub](https://github.com/geerlingguy/docker-debian8-ansible) |
| [geerlingguy/docker-ubi8-ansible](https://hub.docker.com/r/geerlingguy/docker-ubi8-ansible/) | [![Build Status](https://travis-ci.com/geerlingguy/docker-ubi8-ansible.svg?branch=master)](https://travis-ci.com/geerlingguy/docker-ubi8-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-ubi8-ansible) |
| [geerlingguy/docker-amazonlinux2-ansible](https://hub.docker.com/r/geerlingguy/docker-amazonlinux2-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-amazonlinux2-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-amazonlinux2-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-amazonlinux2-ansible) |
| [geerlingguy/docker-fedora32-ansible](https://hub.docker.com/r/geerlingguy/docker-fedora32-ansible/) | [![Build Status](https://travis-ci.com/geerlingguy/docker-fedora32-ansible.svg?branch=master)](https://travis-ci.com/geerlingguy/docker-fedora32-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-fedora32-ansible) |
| [geerlingguy/docker-fedora31-ansible](https://hub.docker.com/r/geerlingguy/docker-fedora31-ansible/) | [![Build Status](https://travis-ci.com/geerlingguy/docker-fedora31-ansible.svg?branch=master)](https://travis-ci.com/geerlingguy/docker-fedora31-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-fedora31-ansible) |
| [geerlingguy/docker-fedora30-ansible](https://hub.docker.com/r/geerlingguy/docker-fedora30-ansible/) | [![Build Status](https://travis-ci.com/geerlingguy/docker-fedora30-ansible.svg?branch=master)](https://travis-ci.com/geerlingguy/docker-fedora30-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/docker-fedora30-ansible) |
| [geerlingguy/docker-fedora29-ansible](https://hub.docker.com/r/geerlingguy/docker-fedora29-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-fedora29-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-fedora29-ansible) | &#10007; | [GitHub](https://github.com/geerlingguy/docker-fedora29-ansible) |
| [geerlingguy/docker-fedora27-ansible](https://hub.docker.com/r/geerlingguy/docker-fedora27-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-fedora27-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-fedora27-ansible) | &#10007; | [GitHub](https://github.com/geerlingguy/docker-fedora27-ansible) |
| [geerlingguy/docker-fedora24-ansible](https://hub.docker.com/r/geerlingguy/docker-fedora24-ansible/) | [![Build Status](https://travis-ci.org/geerlingguy/docker-fedora24-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/docker-fedora24-ansible) | &#10007; | [GitHub](https://github.com/geerlingguy/docker-fedora24-ansible) |

See also: [Testing your roles with Molecule](https://www.jeffgeerling.com/blog/2018/testing-your-ansible-roles-molecule)

<a href="#">Back to Top</a>

## <a name="collections"></a>Ansible Collections

| Name | Test Status | Maintained? | Repository |
| ---- | ----------- | ----------- | ---------- |
| [geerlingguy.k8s](https://galaxy.ansible.com/geerlingguy/k8s) | [![Build Status](https://travis-ci.com/geerlingguy/ansible-collection-k8s.svg?branch=master)](https://travis-ci.com/geerlingguy/ansible-collection-k8s) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-collection-k8s) |
| [geerlingguy.php_roles](https://galaxy.ansible.com/geerlingguy/php_roles) | [![Build Status](https://travis-ci.com/geerlingguy/ansible-collection-php_roles.svg?branch=master)](https://travis-ci.com/geerlingguy/ansible-collection-php_roles) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-collection-php_roles) |

<a href="#">Back to Top</a>

## <a name="roles"></a>Ansible Roles

| Name | Test Status | Maintained? | Repository |
| ---- | ----------- | ----------- | ---------- |
| [geerlingguy.adminer](https://galaxy.ansible.com/geerlingguy/adminer) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-adminer.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-adminer) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-adminer) |
| [geerlingguy.ansible](https://galaxy.ansible.com/geerlingguy/ansible) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-ansible.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-ansible) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-ansible) |
| [geerlingguy.apache](https://galaxy.ansible.com/geerlingguy/apache) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-apache.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-apache) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-apache) |
| [geerlingguy.apache-php-fpm](https://galaxy.ansible.com/geerlingguy/apache-php-fpm) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-apache-php-fpm.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-apache-php-fpm) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-apache-php-fpm) |
| [geerlingguy.aws-inspector](https://galaxy.ansible.com/geerlingguy/aws-inspector) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-aws-inspector.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-aws-inspector) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-aws-inspector) |
| [geerlingguy.awx](https://galaxy.ansible.com/geerlingguy/awx) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-awx.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-awx) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-awx) |
| [geerlingguy.backup](https://galaxy.ansible.com/geerlingguy/backup) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-backup.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-backup) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-backup) |
| [geerlingguy.bad_judgement](https://galaxy.ansible.com/geerlingguy/bad_judgement) | [![Build Status](https://travis-ci.com/geerlingguy/ansible-role-bad_judgement.svg?branch=master)](https://travis-ci.com/geerlingguy/ansible-role-bad_judgement) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-bad_judgement) |
| [geerlingguy.blackfire](https://galaxy.ansible.com/geerlingguy/blackfire) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-blackfire.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-blackfire) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-blackfire) |
| [geerlingguy.certbot](https://galaxy.ansible.com/geerlingguy/certbot) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-certbot.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-certbot) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-certbot) |
| [geerlingguy.clamav](https://galaxy.ansible.com/geerlingguy/clamav) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-clamav.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-clamav) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-clamav) |
| [geerlingguy.collectd-signalfx](https://galaxy.ansible.com/geerlingguy/collectd-signalfx) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-collectd-signalfx.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-collectd-signalfx) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-collectd-signalfx) |
| [geerlingguy.composer](https://galaxy.ansible.com/geerlingguy/composer) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-composer.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-composer) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-composer) |
| [geerlingguy.daemonize](https://galaxy.ansible.com/geerlingguy/daemonize) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-daemonize.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-daemonize) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-daemonize) |
| [geerlingguy.docker](https://galaxy.ansible.com/geerlingguy/docker) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-docker.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-docker) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-docker) |
| [geerlingguy.docker_arm](https://galaxy.ansible.com/geerlingguy/docker_arm) | [![Build Status](https://travis-ci.com/geerlingguy/ansible-role-docker_arm.svg?branch=master)](https://travis-ci.com/geerlingguy/ansible-role-docker_arm) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-docker_arm) |
| [geerlingguy.dotfiles](https://galaxy.ansible.com/geerlingguy/dotfiles) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-dotfiles.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-dotfiles) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-dotfiles) |
| [geerlingguy.drupal](https://galaxy.ansible.com/geerlingguy/drupal) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-drupal.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-drupal) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-drupal) |
| [geerlingguy.drupal-console](https://galaxy.ansible.com/geerlingguy/drupal-console) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-drupal-console.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-drupal-console) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-drupal-console) |
| [geerlingguy.drush](https://galaxy.ansible.com/geerlingguy/drush) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-drush.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-drush) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-drush) |
| [geerlingguy.ecr_container_build](https://galaxy.ansible.com/geerlingguy/ecr_container_build) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-ecr_container_build.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-ecr_container_build) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-ecr_container_build) |
| [geerlingguy.elasticsearch](https://galaxy.ansible.com/geerlingguy/elasticsearch) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-elasticsearch.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-elasticsearch) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-elasticsearch) |
| [geerlingguy.elasticsearch-curator](https://galaxy.ansible.com/geerlingguy/elasticsearch-curator) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-elasticsearch-curator.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-elasticsearch-curator) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-elasticsearch-curator) |
| [geerlingguy.exim](https://galaxy.ansible.com/geerlingguy/exim) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-exim.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-exim) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-exim) |
| [geerlingguy.fathom](https://galaxy.ansible.com/geerlingguy/fathom) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-fathom.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-fathom) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-fathom) |
| [geerlingguy.filebeat](https://galaxy.ansible.com/geerlingguy/filebeat) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-filebeat.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-filebeat) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-filebeat) |
| [geerlingguy.firewall](https://galaxy.ansible.com/geerlingguy/firewall) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-firewall.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-firewall) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-firewall) |
| [geerlingguy.fluentd](https://galaxy.ansible.com/geerlingguy/fluentd) | [![Build Status](https://travis-ci.com/geerlingguy/ansible-role-fluentd.svg?branch=master)](https://travis-ci.com/geerlingguy/ansible-role-fluentd) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-fluentd) |
| [geerlingguy.git](https://galaxy.ansible.com/geerlingguy/git) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-git.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-git) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-git) |
| [geerlingguy.github-users](https://galaxy.ansible.com/geerlingguy/github-users) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-github-users.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-github-users) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-github-users) |
| [geerlingguy.gitlab](https://galaxy.ansible.com/geerlingguy/gitlab) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-gitlab.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-gitlab) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-gitlab) |
| [geerlingguy.glusterfs](https://galaxy.ansible.com/geerlingguy/glusterfs) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-glusterfs.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-glusterfs) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-glusterfs) |
| [geerlingguy.gogs](https://galaxy.ansible.com/geerlingguy/gogs) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-gogs.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-gogs) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-gogs) |
| [geerlingguy.haproxy](https://galaxy.ansible.com/geerlingguy/haproxy) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-haproxy.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-haproxy) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-haproxy) |
| [geerlingguy.hdparm](https://galaxy.ansible.com/geerlingguy/hdparm) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-hdparm.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-hdparm) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-hdparm) |
| [geerlingguy.helm](https://galaxy.ansible.com/geerlingguy/helm) | [![Build Status](https://travis-ci.com/geerlingguy/ansible-role-helm.svg?branch=master)](https://travis-ci.com/geerlingguy/ansible-role-helm) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-helm) |
| [geerlingguy.homebrew](https://galaxy.ansible.com/geerlingguy/homebrew) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-homebrew.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-homebrew) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-homebrew) |
| [geerlingguy.htpasswd](https://galaxy.ansible.com/geerlingguy/htpasswd) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-htpasswd.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-htpasswd) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-htpasswd) |
| [geerlingguy.java](https://galaxy.ansible.com/geerlingguy/java) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-java.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-java) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-java) |
| [geerlingguy.jenkins](https://galaxy.ansible.com/geerlingguy/jenkins) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-jenkins.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-jenkins) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-jenkins) |
| [geerlingguy.k8s_manifests](https://galaxy.ansible.com/geerlingguy/k8s_manifests) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-k8s_manifests.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-k8s_manifests) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-k8s_manifests) |
| [geerlingguy.kibana](https://galaxy.ansible.com/geerlingguy/kibana) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-kibana.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-kibana) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-kibana) |
| [geerlingguy.kubernetes](https://galaxy.ansible.com/geerlingguy/kubernetes) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-kubernetes.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-kubernetes) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-kubernetes) |
| [geerlingguy.logstash](https://galaxy.ansible.com/geerlingguy/logstash) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-logstash.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-logstash) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-logstash) |
| [geerlingguy.logstash-forwarder](https://galaxy.ansible.com/geerlingguy/logstash-forwarder) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-logstash-forwarder.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-logstash-forwarder) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-logstash-forwarder) |
| [geerlingguy.mailhog](https://galaxy.ansible.com/geerlingguy/mailhog) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-mailhog.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-mailhog) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-mailhog) |
| [geerlingguy.mas](https://galaxy.ansible.com/geerlingguy/mas) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-mas.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-mas) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-mas) |
| [geerlingguy.memcached](https://galaxy.ansible.com/geerlingguy/memcached) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-memcached.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-memcached) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-memcached) |
| [geerlingguy.munin](https://galaxy.ansible.com/geerlingguy/munin) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-munin.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-munin) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-munin) |
| [geerlingguy.munin-node](https://galaxy.ansible.com/geerlingguy/munin-node) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-munin-node.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-munin-node) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-munin-node) |
| [geerlingguy.mysql](https://galaxy.ansible.com/geerlingguy/mysql) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-mysql.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-mysql) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-mysql) |
| [geerlingguy.nfs](https://galaxy.ansible.com/geerlingguy/nfs) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-nfs.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-nfs) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-nfs) |
| [geerlingguy.nginx](https://galaxy.ansible.com/geerlingguy/nginx) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-nginx.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-nginx) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-nginx) |
| [geerlingguy.nodejs](https://galaxy.ansible.com/geerlingguy/nodejs) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-nodejs.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-nodejs) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-nodejs) |
| [geerlingguy.ntp](https://galaxy.ansible.com/geerlingguy/ntp) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-ntp.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-ntp) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-ntp) |
| [geerlingguy.packer](https://galaxy.ansible.com/geerlingguy/packer) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-packer.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-packer) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-packer) |
| [geerlingguy.packer-debian](https://galaxy.ansible.com/geerlingguy/packer-debian) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-packer-debian.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-packer-debian) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-packer-debian) |
| [geerlingguy.packer_rhel](https://galaxy.ansible.com/geerlingguy/packer_rhel) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-packer_rhel.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-packer_rhel) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-packer_rhel) |
| [geerlingguy.passenger](https://galaxy.ansible.com/geerlingguy/passenger) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-passenger.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-passenger) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-passenger) |
| [geerlingguy.phergie](https://galaxy.ansible.com/geerlingguy/phergie) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-phergie.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-phergie) | &#10007; | [GitHub](https://github.com/geerlingguy/ansible-role-phergie) |
| [geerlingguy.php](https://galaxy.ansible.com/geerlingguy/php) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php) |
| [geerlingguy.php-memcached](https://galaxy.ansible.com/geerlingguy/php-memcached) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-memcached.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-memcached) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-memcached) |
| [geerlingguy.phpmyadmin](https://galaxy.ansible.com/geerlingguy/phpmyadmin) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-phpmyadmin.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-phpmyadmin) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-phpmyadmin) |
| [geerlingguy.php-mysql](https://galaxy.ansible.com/geerlingguy/php-mysql) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-mysql.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-mysql) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-mysql) |
| [geerlingguy.php-pear](https://galaxy.ansible.com/geerlingguy/php-pear) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-pear.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-pear) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-php-pear) |
| [geerlingguy.php-pecl](https://galaxy.ansible.com/geerlingguy/php-pecl) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-pecl.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-pecl) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-pecl) |
| [geerlingguy.php-pgsql](https://galaxy.ansible.com/geerlingguy/php-pgsql) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-pgsql.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-pgsql) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-pgsql) |
| [geerlingguy.php-redis](https://galaxy.ansible.com/geerlingguy/php-redis) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-redis.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-redis) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-redis) |
| [geerlingguy.php-tideways](https://galaxy.ansible.com/geerlingguy/php-tideways) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-tideways.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-tideways) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-tideways) |
| [geerlingguy.php-versions](https://galaxy.ansible.com/geerlingguy/php-versions) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-versions.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-versions) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-versions) |
| [geerlingguy.php-xdebug](https://galaxy.ansible.com/geerlingguy/php-xdebug) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-xdebug.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-xdebug) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-xdebug) |
| [geerlingguy.php-xhprof](https://galaxy.ansible.com/geerlingguy/php-xhprof) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-php-xhprof.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-php-xhprof) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-php-xhprof) |
| [geerlingguy.pimpmylog](https://galaxy.ansible.com/geerlingguy/pimpmylog) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-pimpmylog.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-pimpmylog) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-pimpmylog) |
| [geerlingguy.pip](https://galaxy.ansible.com/geerlingguy/pip) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-pip.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-pip) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-pip) |
| [geerlingguy.postfix](https://galaxy.ansible.com/geerlingguy/postfix) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-postfix.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-postfix) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-postfix) |
| [geerlingguy.postgresql](https://galaxy.ansible.com/geerlingguy/postgresql) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-postgresql.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-postgresql) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-postgresql) |
| [geerlingguy.puppet](https://galaxy.ansible.com/geerlingguy/puppet) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-puppet.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-puppet) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-puppet) |
| [geerlingguy.rabbitmq](https://galaxy.ansible.com/geerlingguy/rabbitmq) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-rabbitmq.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-rabbitmq) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-rabbitmq) |
| [geerlingguy.raspberry-pi](https://galaxy.ansible.com/geerlingguy/raspberry-pi) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-raspberry-pi.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-raspberry-pi) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-raspberry-pi) |
| [geerlingguy.redis](https://galaxy.ansible.com/geerlingguy/redis) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-redis.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-redis) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-redis) |
| [geerlingguy.repo-dotdeb](https://galaxy.ansible.com/geerlingguy/repo-dotdeb) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-repo-dotdeb.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-repo-dotdeb) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-repo-dotdeb) |
| [geerlingguy.repo-epel](https://galaxy.ansible.com/geerlingguy/repo-epel) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-repo-epel.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-repo-epel) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-repo-epel) |
| [geerlingguy.repo-puias](https://galaxy.ansible.com/geerlingguy/repo-puias) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-repo-puias.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-repo-puias) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-repo-puias) |
| [geerlingguy.repo-remi](https://galaxy.ansible.com/geerlingguy/repo-remi) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-repo-remi.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-repo-remi) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-repo-remi) |
| [geerlingguy.ruby](https://galaxy.ansible.com/geerlingguy/ruby) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-ruby.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-ruby) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-ruby) |
| [geerlingguy.samba](https://galaxy.ansible.com/geerlingguy/samba) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-samba.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-samba) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-samba) |
| [geerlingguy.security](https://galaxy.ansible.com/geerlingguy/security) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-security.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-security) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-security) |
| [geerlingguy.solr](https://galaxy.ansible.com/geerlingguy/solr) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-solr.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-solr) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-solr) |
| [geerlingguy.sonar](https://galaxy.ansible.com/geerlingguy/sonar) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-sonar.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-sonar) | &#10007; | [GitHub](https://github.com/geerlingguy/ansible-role-sonar) |
| [geerlingguy.sonar-runner](https://galaxy.ansible.com/geerlingguy/sonar-runner) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-sonar-runner.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-sonar-runner) | &#10007; | [GitHub](https://github.com/geerlingguy/ansible-role-sonar-runner) |
| [geerlingguy.ssh-chroot-jail](https://galaxy.ansible.com/geerlingguy/ssh-chroot-jail) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-ssh-chroot-jail.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-ssh-chroot-jail) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-ssh-chroot-jail) |
| [geerlingguy.supervisor](https://galaxy.ansible.com/geerlingguy/supervisor) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-supervisor.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-supervisor) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-supervisor) |
| [geerlingguy.svn](https://galaxy.ansible.com/geerlingguy/svn) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-svn.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-svn) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-svn) |
| [geerlingguy.svn2git](https://galaxy.ansible.com/geerlingguy/svn2git) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-svn2git.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-svn2git) | &#33; | [GitHub](https://github.com/geerlingguy/ansible-role-svn2git) |
| [geerlingguy.swap](https://galaxy.ansible.com/geerlingguy/swap) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-swap.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-swap) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-swap) |
| [geerlingguy.tomcat6](https://galaxy.ansible.com/geerlingguy/tomcat6) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-tomcat6.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-tomcat6) | &#10007; | [GitHub](https://github.com/geerlingguy/ansible-role-tomcat6) |
| [geerlingguy.varnish](https://galaxy.ansible.com/geerlingguy/varnish) | [![Build Status](https://travis-ci.org/geerlingguy/ansible-role-varnish.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-varnish) | &#10003; | [GitHub](https://github.com/geerlingguy/ansible-role-varnish) |

<a href="#">Back to Top</a>

## <a name="projects"></a>Ansible Projects

| Name and Link | Test Status | Maintained? |
| ------------- | ----------- | ----------- |
| [Ansible Requirements Updater](https://github.com/geerlingguy/ansible-requirements-updater) | N/A | &#10003; |
| [Mac Development Playbook](https://github.com/geerlingguy/mac-dev-playbook) | [![Build Status](https://travis-ci.org/geerlingguy/mac-dev-playbook.svg?branch=master)](https://travis-ci.org/geerlingguy/mac-dev-playbook) | &#10003; |
| [Packer Boxes](https://github.com/geerlingguy/packer-boxes) | ![Validate Packer JSON files](https://github.com/geerlingguy/packer-boxes/workflows/Validate%20Packer%20JSON%20files/badge.svg) | &#10003; |
| [Drupal VM](https://www.drupalvm.com) | [![Build Status](https://travis-ci.org/geerlingguy/drupal-vm.svg?branch=master)](https://travis-ci.org/geerlingguy/drupal-vm) | &#10003; |
| [Raspberry Pi Dramble](https://www.pidramble.com) | [![Build Status](https://travis-ci.org/geerlingguy/raspberry-pi-dramble.svg?branch=master)](https://travis-ci.org/geerlingguy/raspberry-pi-dramble) | &#10003; |
| [Drupal Pi](https://github.com/geerlingguy/drupal-pi) | [![Build Status](https://travis-ci.org/geerlingguy/drupal-pi.svg?branch=master)](https://travis-ci.org/geerlingguy/drupal-pi) | &#10003; |
| [Turing Pi Cluster](https://github.com/geerlingguy/turing-pi-cluster) | [![Build Status](https://github.com/geerlingguy/turing-pi-cluster/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/geerlingguy/turing-pi-cluster/actions?query=workflow%3ACI) | &#33; |
| [Ansible Vagrant Examples](https://github.com/geerlingguy/ansible-vagrant-examples) | N/A | &#33; |

Also see [all my blog posts about Ansible](https://www.jeffgeerling.com/category/ansible) and [all my YouTube videos about Ansible](https://www.youtube.com/playlist?list=PL2_OBreMn7FplshFCWYlaN2uS8et9RjNG).

<a href="#">Back to Top</a>

## <a name="presentations"></a>Ansible Videos and Presentations

| Place and Date | Title |
| -------------- | ----- |
| Meetup<br><span class="date">January 14, 2014</span> | [Local Dev on Virtual Machines - Vagrant, VirtualBox and Ansible](https://www.jeffgeerling.com/blog/virtualbox-vagrant-and-ansible-local-development) |
| DrupalCon Austin<br><span class="date">June 5, 2014</span> | [DevOps for Humans: Ansible for Drupal Deployment Victory!](https://www.jeffgeerling.com/blog/devops-humans-ansible-presentation-drupalcon)
| YouTube<br><span class="date">March 8, 2015</span> | [Ansible serial/forks demo on a Cluster of Raspberry Pis](https://www.youtube.com/watch?v=rRJQiHydVG4) |
| MidCamp 2015<br><span class="date">March 21, 2015</span> | [Ansible + Drupal: A Fortuitous DevOps Match](https://www.jeffgeerling.com/blog/midcamp-2015-ansible-drupal-8-presentation) |
| YouTube<br><span class="date">July 14, 2015</span> | [Ansible 101 on a Cluster of Raspberry Pi 2s](https://www.youtube.com/watch?v=ZNB1at8mJWY) |
| YouTube<br><span class="date">July 27, 2015</span> | [Nginx Load Balancer Visualization on a Cluster of Raspberry Pis](https://www.youtube.com/watch?v=7Tf2f5gdO4I) |
| php[tek] 2016<br><span class="date">May 25, 2016</span> | [Highly Available Drupal on a Raspberry Pi Cluster](https://www.jeffgeerling.com/blog/2016/highly-available-drupal-on-raspberry-pi-cluster-phptek-2016-session) |
| AnsibleFest SF 2016<br><span class="date">July 28, 2016</span> | [Ansible Roles for Fun and Profit!](https://www.ansible.com/ansible-roles-by-acquia) |
| MidCamp 2018<br><span class="date">March 10, 2018</span> | [Jenkins or: How I learned to stop worrying and love automation](https://www.midcamp.org/2018/topic-proposal/jenkins-or-how-i-learned-stop-worrying-and-love-automation) |
| AnsibleFest Austin 2018<br><span class="date">August 21, 2018</span> | [Make your Ansible playbooks flexible, maintainable, and scalable](https://www.youtube.com/watch?v=kNDL13MJG6Y) |
| AnsibleFest Atlanta 2019<br><span class="date">September 25, 2019</span> | [There's a Role for that! How to evaluate community roles for your playbook](https://www.jeffgeerling.com/blog/2019/how-evaluate-community-ansible-roles-your-playbooks) |
| DrupalCon Seattle 2019<br><span class="date">November 26, 2019</span> | [Everything I know about Kubernetes I learned from a cluster of Raspberry Pis](https://www.jeffgeerling.com/blog/2019/everything-i-know-about-kubernetes-i-learned-cluster-raspberry-pis) |
| YouTube<br><span class="date">April 2020</span> | [Ansible 101 streaming series](https://www.jeffgeerling.com/blog/2020/ansible-101-jeff-geerling-youtube-streaming-series) |

<a href="#">Back to Top</a>

## Inspiration

This site was inspired by [Robert de Bock's similar Ansible roles site](https://robertdebock.nl).
