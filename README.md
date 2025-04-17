# What is this?

[![Release](https://github.com/amentumcms/Collector-Busybox-IB/actions/workflows/collect.yml/badge.svg?branch=main)](https://github.com/amentumcms/Collector-Busybox-IB-IB/actions/workflows/collect.yml)

This is a project that automatically collects artifacts to ease in air-gapped transfer from the internet.

It runs actions manually or on Push and creates a release.

In this case, it collects the source code repositories and the associated container images via skopeo & gh for:

- dso.mil IronBank Busybox (frontier) Hardened container image
- dso.mil IronBank Busybox (chainguard) Hardened container image
- dso.mil IronBank Busybox (Alpine) Hardened container image
- Git Hub k9s CLI latest release artifacts 
