# BaGet Helm Chart

BaGet is a lightweight NuGet and symbol server. It is open source, cross-platform, and cloud ready!

## Introduction

This chart bootstraps a BagGet instance. This chart don't include database deployment.

## Prerequisites

- Kubernetes 1.10+

## Installing the chart

To install the chart:

```bash
$ helm install . baget
```

The above command deploys Sonarqube on the Kubernetes cluster in the default configuration.

## Uninstalling the chart

To uninstall/delete the deployment:

```bash
$ helm list
NAME       	REVISION	UPDATED                 	STATUS  	CHART          	NAMESPACE
baget      	          Mon Oct  2 15:05:44 2017	DEPLOYED	baget-0.1.0	    default
$ helm delete baget
```

## References

- [BaGet GitHub repository](https://github.com/loic-sharma/BaGet)
- [BaGet Web](https://loic-sharma.github.io/BaGet/)
- [BaGet DockerHub](https://hub.docker.com/r/loicsharma/baget)
