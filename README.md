falco-docker
============

Dockerfile source for Falco [docker](https://docker.io) image.

# Upstream

This source repo was originally copied from:
https://github.com/falcosecurity/falco/tree/master/docker/falco


# Disclaimer

This is not an official Google product.

# <a name="about"></a>About

This image contains an installation of Falco

For more information, see the
[Official Image Marketplace Page](https://console.cloud.google.com/marketplace/product/google/falco).

### Prerequisites

Configure [gcloud](https://cloud.google.com/sdk/gcloud/) as a Docker credential helper:

```shell
gcloud auth configure-docker
```
### Pull command

```shell
docker -- pull marketplace.gcr.io/google/falco
```
Dockerfile for this image can be found [here](https://github.com/GoogleCloudPlatform/click-to-deploy/tree/master/docker/falco/0/debian10/0.31/).

