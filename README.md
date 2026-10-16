# infrastructure-gitops (moved)

This repository is archived. Its contents, with their history, now live in the `gitops/` directory of
[secure-software-supplychain](https://github.com/blanketops/secure-software-supplychain/tree/main/gitops), and
Argo CD deploys from there.

| Was | Now |
|---|---|
| `argocd/secure-build-engine.yaml`, `platforms/secure-build-engine/` | `gitops/argocd/supplychain.yaml`, `gitops/supplychain/` |
| `argocd/secure-read-engine.yaml`, `platforms/secure-read-engine/` | `gitops/argocd/policy.yaml`, `gitops/policy/` |
| `argocd/read-workloads.yaml`, `workloads/for-kaniko-app/` (namespace `workloads`) | `gitops/argocd/for-kaniko-app.yaml`, `gitops/for-kaniko-app/` (namespace `dev`) |
| `hack/` | `gitops/hack/` |
