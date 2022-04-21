# GCP Sandboxes

[SuperHub] is an open source tool that helps cloud practitioners to automate deployments of [GCP] sandbox environemnts. It offers:

- **Sandbox Templates** - Several supported sandboxes built on cloud native stack:
  - [GKE]
  - [VM] with Web Server
  - [Cloud SQL]
  - [Cloud Composer]
- **One-click Deployment** of complete sandbox environments to [Google Cloud Platform]
- **Load Generator** - a component that produces synthetic traffic on a demo application

## How to deploy a Sandbox Environment

Sign in to your [GCP] account using [Google Cloud Platform web console](https://console.cloud.google.com/). If you have a [Cloud Shell](https://cloud.google.com/shell) session running, clicking the button will restart it.

## Quick Start

Install supported sandboxes using the following commands:

```shell
hub stack init
hub stack deploy
```

[SuperHub]: https://superhub.io
[GCP]: https://cloud.google.com/gcp/
[Google Cloud Platform]: https://cloud.google.com/gcp/
[Cloud SQL]: https://cloud.google.com/sql/
[Cloud Composer]: https://cloud.google.com/composer/
[GKE]: https://cloud.google.com/kubernetes-engine/
[VM]: https://cloud.google.com/compute/
