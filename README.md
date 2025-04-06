# Harbor Helm Chart (Standalone)

This Helm chart deploys Harbor container registry with standalone PostgreSQL and Redis components.

## Prerequisites

- Kubernetes 1.19+
- Helm 3.2.0+
- PV provisioner support in the underlying infrastructure

## Installing the Chart

To install the chart with the release name `my-harbor`:

```bash
helm install my-harbor ./harbor
