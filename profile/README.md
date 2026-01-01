## SumiCare

**[Sumi.care](https://sumi.care/oss)** OSS Projects

**[Kachō](https://github.com/sumicare/kacho)** Backstage Ecosystem <br/>
Business Platform and tools inspired by traditional Japanese flower-and-bird art (花鳥).

 - **[Suzuri](https://github.com/sumicare/suzuri)** — Custom ERP Platform
 - **[Rikka](https://github.com/sumicare/rikka)** — All-in-one Kubernetes metrics solution, unifies and extends [node_exporter](https://github.com/prometheus/node_exporter), [kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) and [metrics-server](https://github.com/kubernetes-sigs/metrics-server)
 - **[Shōka](https://github.com/sumicare/shoka)** — Resource cost and usage reporter, uses [smithy-rs](https://github.com/sumicare/smithy-rs) to generate custom Cloud API clients and unified usage/cost reporters
 - **[Nageire](https://github.com/sumicare/nageire)** — Cost/availability/demand predictor, basically Torch [Forecasting models](https://pytorch-forecasting.readthedocs.io/en/v1.4.0/models.html) port to [burn-rs](https://burn.dev/)
 - **[Moribana](https://github.com/sumicare/moribana)** — Production-ready cluster autoscaler, simplifies Kubernetes autoscaling with OpenTofu
 - **[Jiyūka](https://github.com/sumicare/jiyuka)** — Custom virtual kubelet implementation for third-party GPU hosting providers
 - **[Haboku](https://github.com/sumicare/haboku)** — Collection of cloud-native architecture OpenTofu Modules

## Infrastructure & Tooling

- [smithy-rs](https://github.com/sumicare/smithy-rs) — Native Rust implementation of [Smithy](https://smithy.io/).
- [opentofu-cmp](https://github.com/sumicare/opentofu-cmp) — OpenTofu [configuration management plugin](https://argo-cd.readthedocs.io/en/stable/operator-manual/config-management-plugins) for ArgoCD.
- [terraform-gcp-atlantis](https://github.com/sumicare/terraform-gcp-atlantis) — GCP [Atlantis](https://www.runatlantis.io/) module.
- [universal-asdf-plugin](https://github.com/sumicare/universal-asdf-plugin) — [ASDF plugins](https://github.com/asdf-vm/asdf-plugins) implemented as Golang binary.
- [teerpc-go](https://github.com/sumicare/teerpc-go) / [teerpc-rs](https://github.com/sumicare/teerpc-rs) — Internal [tRPC](https://trpc.io/) scaffolds for Golang and Rust.

## OpenTofu Providers

- [provider-kacho](https://github.com/sumicare/opentofu-provider-kacho) — [Sumi.care](https://sumi.care) [Kachō](https://sumi.care/kacho) provider.
- [provider-gitea](https://github.com/sumicare/opentofu-provider-gitea) — [Gitea](https://about.gitea.com/) provider.
- [provider-kind](https://github.com/sumicare/opentofu-provider-kind) — [Kind](https://kind.sigs.k8s.io/) provider.
