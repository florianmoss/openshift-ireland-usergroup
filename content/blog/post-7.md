---
title: "Meeting #2 - Secure Continuous Delivery with Podman, Buildah, Skopeo"
date: 2021-01-14
draft: false

# post thumb
image: "images/post/post7.png"

# meta description
description: "OpenShift Ireland User Group - Meeting #2"

# taxonomies
categories:
  - "Meeting"
tags:
  - "Meeting 2"
  - "Recordings"
  - "Podman"
  - "Buildah"
  - "Skopeo"

# post type
type: "featured"
---


# Presentation 2: Secure Continuous Delivery with Podman, Buildah, Skopeo
A hands-on demonstration of lessons learned migrating from other container build tools to the RHEL container ecosystem. We aim to explore a set of command-line tools that are able to operate without a container daemon, and namely: Buildah, Podman, Quay and Skopeo.

We will discuss a new set of open-source Container Management Tools starting from a hands-on demonstration. In a nutshell, Buildah builds, Podman runs, Skopeo transfers container images and Quay provides private and public container registries.

Moreover, we will take a look at best practices for building images that can easily be integrated into a CI/CD Pipeline and vulnerability scanning with Clair, thus replacing previous build tools in workflows.

Understand the impact of SELinux, namespaces and cgroups. Move from docker-compose to Podman pods. Build container images for OpenShift Container Platform.

{{< youtube YLOv6YhQXJQ >}}
