### Hi, I'm Baris

DevOps Engineer in Berlin. Off hours I run a small Kubernetes homelab and keep
every bit of it in Git.

#### 🏠 [homelab-infra](https://github.com/barissekerciler/homelab-infra)

My homelab as code: a two-node Talos Linux cluster that Flux reconciles from Git.
No `kubectl apply` by hand, no secrets in the repo, nothing port-forwarded.

- **GitOps:** Flux with image automation; private apps run as a separate Flux tenant
- **Secrets:** OpenBao and the External Secrets Operator
- **Storage:** TrueNAS over iSCSI and NFS (democratic-csi), with volumes pinned in Git
  so a rebuilt cluster finds its old disks
- **Databases:** CloudNativePG, backed up to in-cluster S3 (SeaweedFS)
- **Edge:** Traefik, cert-manager, a Cloudflare tunnel and Tailscale
- **Observability:** kube-prometheus-stack and Grafana, dashboards generated from Python

#### 📫 Elsewhere

[blog.bariss.dev](https://blog.bariss.dev) · [LinkedIn](https://www.linkedin.com/in/barissekerciler)
