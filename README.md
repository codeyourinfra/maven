# maven

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![GitHub release](https://img.shields.io/github/release/codeyourinfra/maven.svg)](https://github.com/codeyourinfra/maven/releases/latest) [![Build status](https://travis-ci.org/codeyourinfra/maven.svg?branch=master)](https://travis-ci.org/codeyourinfra/maven) [![Ansible Role](https://img.shields.io/ansible/role/29234.svg)](https://galaxy.ansible.com/codeyourinfra/maven) [![Ansible Role downloads](https://img.shields.io/ansible/role/d/29234.svg)](https://galaxy.ansible.com/codeyourinfra/maven)

Ansible role to install [Apache Maven](https://maven.apache.org).

## Example Playbook

```yml
---
- hosts: servers
  roles:
    - codeyourinfra.maven
```

## Dependencies

The role is dependent of [Codeyourinfra's Oracle Java 8 Ansible role version 1.0](https://github.com/codeyourinfra/oracle_java8/tree/v1.0), once we need Java to run Maven. Java is so installed before the Maven installation.

## Build process

The build process is performed in [Travis CI](https://travis-ci.org/codeyourinfra/maven). During the build, the role is tested by using [Ubuntu Docker images with Python 3](https://hub.docker.com/r/codeyourinfra/python3).

## Author Information

[@gustavomcarmo](https://github.com/gustavomcarmo) is a contributor of [Codeyourinfra](https://github.com/codeyourinfra). Get on board too! :)
