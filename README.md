# Thomas Zachmann

**Kubernetes platform architect for regulated and sovereign environments**
On-prem · bare-metal · IONOS Cloud / Open Telekom Cloud · Hamburg, Germany

---

I build Kubernetes platforms for environments where security and auditability are
the requirement, not the extra: on-premise, on bare metal, in air-gapped networks,
and on European cloud providers.

Since 2020 I have worked exclusively in regulated settings — federal security
technology, public-sector IT, and banking. My focus is the part most platforms skip:
policy enforcement, secrets management, workload identity, supply-chain evidence,
and the documentation that survives an audit.

Certified **CKS**, **CKA**, **CKAD**. Twenty years of software engineering before that
(SAP, C/C++, Go), which is why the automation here is written rather than assembled.

---

## Repositories

### [onprem-rke2-platform-reference](https://github.com/thomaszachmann/onprem-rke2-platform-reference)

Production-grade Ansible automation for a highly available RKE2 cluster on Ubuntu 24.04:
embedded etcd, kube-vip for control-plane HA, Longhorn distributed storage, cert-manager,
Kyverno policy enforcement in enforce mode, namespace-isolating NetworkPolicies, audit
logging, and a Prometheus/Grafana stack.

Includes the architecture, the security model, the backup strategy, and a step-by-step
deployment path.

`ansible` · `rke2` · `kubernetes` · `kyverno` · `longhorn` · `on-premise` · `hardening`

### [aws-k8s-platform-reference](https://github.com/thomaszachmann/aws-k8s-platform-reference)

Terraform modules for an EKS platform — network, IAM, security and cluster layers kept
separate — with a hardening checklist and secrets-management documentation.

`terraform` · `aws` · `eks` · `kubernetes` · `iam` · `security`

---

## What I work on

| Area | Detail |
|---|---|
| **Kubernetes** | On-prem and bare metal (RKE2, Kubespray, OpenShift, Rancher), managed (EKS), MetalLB, Istio, Helm, Kustomize |
| **Security & policy** | Kyverno, HashiCorp Vault, Keycloak, Trivy, Harbor, Dependency Track, cert-manager |
| **Automation & IaC** | Ansible, Terraform, Crossplane, Go, Python |
| **GitOps & CI/CD** | Argo CD, Flux, GitLab CI, Jenkins, GitHub Actions |
| **Observability** | Prometheus, Grafana, Loki, Tempo, Elastic |
| **Sovereign platforms** | IONOS Cloud, Open Telekom Cloud, on-prem virtualisation |

---

## How I work

Infrastructure belongs in version control. Automation has to be reproducible or it is
not automation. Security is designed in, not bolted on afterwards. Monitoring is decided
before production, not after the first incident. And a platform that nobody but its
author can operate has failed, however elegant it is — so the handover documentation is
part of the deliverable, not an afterthought.

---

## Kurzprofil (DE)

Freiberuflicher Plattform-Architekt aus Hamburg. Schwerpunkt: Kubernetes in regulierten
und souveränen Umgebungen — On-Prem, Bare-Metal und auf europäischen Cloud-Plattformen.
Zertifiziert als CKS, CKA und CKAD. Seit 2020 durchgängig in Umfeldern mit erhöhten
Anforderungen an Sicherheit, Nachweisbarkeit und Governance.

**Sprachen:** Deutsch und Dänisch (Muttersprache), Englisch (fließend)

---

## Contact

- Website: <https://thomaszachmann.de>
- E-Mail: thomas@zachmann.work
