# Renegade-Master Helm Charts

## Description

This repo is a collection of Helm Charts.

## Usage

[Helm](https://helm.sh) must be installed to use the Charts. Please refer to Helm's
[documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```sh
helm repo add renegade-master https://renegade-master.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages. You
can then run `helm search repo renegade-master` to see the Charts.

To install a Helm Chart:

```sh
helm install <chart-name> renegade-master/<chart-name> 
```

To uninstall the chart:

```sh
helm delete <chart-name> 
```
