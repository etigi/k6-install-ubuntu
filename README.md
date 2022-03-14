# k6-install-ubuntu

A github action to install k6 on GitHub ubuntu runners

## Why?

The official Grafana GitHub actions for K6 install _and_ run
the k6 binary.

This action installs only, without running, so the workflow can
do what it wants with k6, like invoke it via a build script or something.

Also, this only installs for the GitHub Unbuntu runners.

## How?

This runner is simply packing the [official instructions](https://k6.io/docs/getting-started/installation/#debian-ubuntu)
for Debian/Ubuntu into a composite GitHub action.
