---
title: 15-05 Podman, Buildah and Skopeo
date: 08/15/23
---

**Podman** is a container engine that is OCI-compliant and is a drop-in replacement for Docker.

* Podman is daemon-less where Docker uses a container daemon
* Podman allows you to create pods like K8, Docker does not have pods
* Podman only replaces one part of Docker. Podman is to be used alongside Buildah and Skopeo

**Buildah** is a tool used to build OCI Images

**Skopeo** is a tool for moving container images between different types of container storages
