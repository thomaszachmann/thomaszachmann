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

## Books

### [Vault in Practice](https://leanpub.com/vault-in-practice)

*A Hands-On Lab Guide to HashiCorp Vault and OpenBao.* Twenty-four chapters, each ending
in a working lab that runs on a laptop in Docker: initialising a cluster and splitting the
key with Shamir's Secret Sharing, policies that fail before they work, dynamic database
credentials, a private CA issuing 24-hour certificates, transit encryption, four ways of
delivering secrets into Kubernetes, and a three-node Raft cluster whose quorum you break
on purpose.

Five chapters ask you to destroy your own installation and recover it, because that is the
part a reference manual cannot teach. Appendix F maps every published HashiCorp Certified:
Vault Associate objective to a chapter and a lab. 581 pages.

`vault` · `openbao` · `secrets-management` · `pki` · `kubernetes` · `docker`

### [Enterprise AI Platform — Lab Guide](https://leanpub.com/enterprise-ai-platform)

GPU infrastructure, model serving, the AI gateway, governance and the cost model — what
lies between a proof of concept and an AI platform a company can actually operate. 386
pages, 23 labs with vLLM, KServe, LiteLLM, the NVIDIA GPU Operator, Keycloak, OpenBao,
Argo CD and pgvector, including the calculations that decide whether a platform is
affordable to run.

Written for platform engineers, not for data scientists. A German edition is available
free of charge at [thomaszachmann.de/buch](https://thomaszachmann.de/buch).

`ai-platform` · `llm` · `vllm` · `kserve` · `gpu-operator` · `kubernetes` · `finops`

Runnable companion code is in [books](https://github.com/thomaszachmann/books).

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

**Bücher:** *Vault in Practice* — 581 Seiten zu HashiCorp Vault und OpenBao — sowie
*Enterprise AI Platform — Lab Guide* zu GPU-Infrastruktur, Model Serving, AI Gateway,
Governance und FinOps. Vom zweiten Buch steht die deutsche Fassung kostenlos unter
[thomaszachmann.de/buch](https://thomaszachmann.de/buch), beide englischen Ausgaben
erscheinen bei Leanpub.

**Sprachen:** Deutsch und Dänisch (Muttersprache), Englisch (fließend)

---

## Contact

- Website: <https://thomaszachmann.de>
- LinkedIn: <https://www.linkedin.com/in/thomaszachmann>
- E-Mail: thomas@zachmann.work
