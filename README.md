# gcb-helper-landscaper

This repo creates a Docker image to be used for steps in [Google Cloud Container Builder](https://cloud.google.com/container-builder/docs/).

Helm 2.2.2 / gcloud / kubectl / landscaper

## Usage

`helm`, `gcloud`, `kubectl` and `landscaper` are all available.

Additionally, `helm_install_or_upgrade` is on the path, which can be used as an
idemptotent `install`, until Helm gets its own proper implementation, tracked by
[this issue](https://github.com/kubernetes/helm/issues/1042).
