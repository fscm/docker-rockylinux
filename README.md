# Rocky Linux for Docker

A small Rocky Linux base image designed for use in containers.

All non-required packages were removed to create this small image. When using
this image you may have to install some of the packages that usually are
installed on a regular Rocky Linux image.

## Supported tags

* `8`, `latest`

## What is Rocky Linux ?

> Rocky Linux is a community enterprise operating system designed to be 100% bug-for-bug compatible with America's top enterprise Linux distribution now that its downstream partner has shifted direction. It is under intensive development by the community. Rocky Linux is led by Gregory Kurtzer, founder of the CentOS project. Contributors are asked to reach out using the communication options offered on this site.

*from* [rockylinux.org](https://rockylinux.org)

## Getting Started

There are a couple of things needed for the script to work.

### Prerequisites

Docker, either the Community Edition (CE) or Enterprise Edition (EE), needs to
be installed on your local computer.

#### Docker

Docker installation instructions can be found
[here](https://docs.docker.com/install/).

### Usage

To start a container with this image and run a shell use the following
command (the container will be deleted after exiting the shell):

```shell
docker container run --rm --interactive --tty fscm/rockylinux bash
```

## Build

Build instructions can be found
[here](https://github.com/fscm/docker-rockylinux/blob/master/README.build.md).

## Versioning

This project uses [SemVer](http://semver.org/) for versioning. For the versions
available, see the [tags on this repository](https://github.com/fscm/docker-rockylinux/tags).

## Authors

* **Frederico Martins** - [fscm](https://github.com/fscm)

See also the list of [contributors](https://github.com/fscm/docker-rockylinux/contributors)
who participated in this project.
