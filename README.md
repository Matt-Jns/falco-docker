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
=======
|DRUPAL_DB_NAME | Database name that Drupal will use to connect with the database. |
|ALLOW_EMPTY_PASSWORD | It can be used to allow blank passwords. |
|MYSQL_USER | Database user. |
|MYSQL_DATABASE | Database name. |
|MYSQL_ALLOW_EMPTY_ROOT_PASSWORD|option for empty password. | 
|MYSQL_HOST|Database host name. |
|MYSQL_PASSWORD|Database password. |
|MYSQL_ROOT_PASSWORD| Database root password .|
 
## <a name="references-volumes"></a>Volumes

These are the filesystem paths used by the container image.

| **Path** | **Description** |
|:---------|:----------------|
|/var/www/html| All Drupal files are installed here containing user uploaded data, themes, profiles and modules. |
