# helm-docker

Helm 2.2.2 and gcloud / kubectl

## Usage

`helm`, `gcloud` and `kubectl` are all available.

Additionally, `helm_install_or_upgrade` is on the path, which can be used as an
idemptotent `install`, until Helm gets its own proper implementation, tracked by
[this issue](https://github.com/kubernetes/helm/issues/1042).

## GCP Container Builder

This image was designed to be used with GCP Container Builder as a step to deploy Helm Charts.

For a use example see: https://github.com/Simon-Ince/gcp-container-builder-with-php-composer/tree/helm
