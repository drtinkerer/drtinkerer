<div align="center">

```
██████╗ ██╗  ██╗██╗   ██╗███████╗██╗  ██╗ █████╗ ███╗   ██╗
██╔══██╗██║  ██║██║   ██║██╔════╝██║  ██║██╔══██╗████╗  ██║
██████╔╝███████║██║   ██║███████╗███████║███████║██╔██╗ ██║
██╔══██╗██╔══██║██║   ██║╚════██║██╔══██║██╔══██║██║╚██╗██║
██████╔╝██║  ██║╚██████╔╝███████║██║  ██║██║  ██║██║ ╚████║
╚═════╝ ╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝
```

**`$ kubectl describe engineer bhushan-rane`**

</div>

```yaml
apiVersion: v1
kind: Engineer
metadata:
  name: bhushan-rane
  labels:
    role: Senior Platform Engineer
    location: Pune, India
    brand: "Hacker · Gamer · Musician · Ponderer"
spec:
  experience: 11 years
  currentRole: Senior DevOps Engineer @ Ollion
  focus:
    - Kubernetes Platform Engineering
    - Identity & Access Management
    - GitOps & Infrastructure Automation
    - Self-Hosted Infrastructure
  superpowers:
    - Kubestronaut (all 5 CNCF K8s certifications)
    - 4x Google Cloud Professional certifications
    - Bare metal Kubernetes bootstrapper
    - Open source builder
```

---

<div align="center">

## Certifications

[![CKA](https://img.shields.io/badge/CKA-Certified_Kubernetes_Administrator-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://www.cncf.io/certification/cka/)
[![CKS](https://img.shields.io/badge/CKS-Certified_Kubernetes_Security_Specialist-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://www.cncf.io/certification/cks/)
[![CKAD](https://img.shields.io/badge/CKAD-Certified_Kubernetes_App_Developer-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://www.cncf.io/certification/ckad/)
[![KCNA](https://img.shields.io/badge/KCNA-Kubernetes_Cloud_Native_Associate-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://www.cncf.io/certification/kcna/)
[![KCSA](https://img.shields.io/badge/KCSA-Kubernetes_Cloud_Native_Security_Associate-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://training.linuxfoundation.org/certification/kubernetes-and-cloud-native-security-associate-kcsa/)

**⎈ [Kubestronaut](https://www.cncf.io/training/kubestronaut/)**

<br/>

[![GCP Architect](https://img.shields.io/badge/GCP-Professional_Cloud_Architect-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://cloud.google.com/certification/cloud-architect)
[![GCP Security](https://img.shields.io/badge/GCP-Professional_Cloud_Security_Engineer-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://cloud.google.com/certification/cloud-security-engineer)
[![GCP Network](https://img.shields.io/badge/GCP-Professional_Cloud_Network_Engineer-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://cloud.google.com/certification/cloud-network-engineer)
[![GCP DevOps](https://img.shields.io/badge/GCP-Professional_Cloud_DevOps_Engineer-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://cloud.google.com/certification/cloud-devops-engineer)
[![AWS SAA](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/certified-solutions-architect-associate/)

</div>

---

## `$ cat /etc/career-highlights`

```
✦ Led 2-year Swiss WealthTech cloud migration as sole engineer → $200K+ revenue
  Hetzner/Azure → GCP, 15+ GKE clusters, Fleet API, ArgoCD Autopilot
  HA VPN → Dedicated Partner Interconnect @ Equinix Frankfurt (~1ms latency)

✦ Bootstrapped 10-node bare metal Kubernetes cluster at Sugarbox Networks
  Full lifecycle: provisioning, OS, networking, control plane, middleware upgrades

✦ Built HealthD — automated incident detection system in Python
  Monitored 200+ edge/CDN nodes, auto-created JIRA tickets → 70% MTTR reduction

✦ 30+ component homelab on OKE, fully GitOps managed via ArgoCD + Kustomize
  Zitadel OIDC integrated with 10+ services, zero-trust networking with NetBird

✦ Published open-source NetBird Python client library on PyPI
  11 resources, 98% test coverage, network visualization (Mermaid, Graphviz)
```

---

## `$ ls -la /skills`

<table>
<tr>
<td valign="top" width="33%">

**Kubernetes & Cloud**
```
kubernetes    ████████████ expert
gcp           ████████████ expert
argocd        ████████████ expert
terraform     ███████████░ strong
aws           ████████░░░░ solid
ansible       ████████░░░░ solid
helm          ███████░░░░░ solid
istio         █████░░░░░░░ learning
```

</td>
<td valign="top" width="33%">

**Platform & Tooling**
```
envoy-gateway ████████████ expert
cert-manager  ████████████ expert
external-dns  ████████████ expert
gitops        ████████████ expert
ci-cd         ███████████░ strong
harbor        ████████░░░░ solid
backstage     ███████░░░░░ solid
```

</td>
<td valign="top" width="33%">

**Code & Identity**
```
python        ████████████ expert
bash          ████████████ expert
go            ████████░░░░ solid
hcl           ████████░░░░ solid
oauth2-oidc   ███████████░ strong
zero-trust    ██████████░░ strong
postgresql    ███████░░░░░ solid
```

</td>
</tr>
</table>

---

## `$ git log --oneline --projects`

| Project | Stack | Description |
|---------|-------|-------------|
| [**NetBird Python Client**](https://pypi.org/project/netbird/) | Python, PyPI | Unofficial API client. 11 resources, 98% test coverage, network visualization |
| [**AWS Landing Zone**](https://github.com/ollionorg/aws-landing-zone) | Terraform | Multi-account, multi-region AWS with security defaults. Led team of 4 |
| **AI Cloud Sandbox Provisioner** | Go, Python, FastAPI, Next.js | Multi-cloud (GCP/AWS/Azure/OCI) sandbox via conversational AI. 6-layer guardrail system |
| **The Self Hosted Engineer** | K8s, OKE, ArgoCD | Homelab guide — Raspberry Pi, Oracle Cloud, NetBird, zero-trust infra |
| **GCP Security Comply 360** | Python, Gen AI, MCP | Security compliance with NIST/CIS benchmarking via LLM |
| **CloudPoet Platform** | Go, Python | Personal SaaS — CLI with PKCE OAuth2, RFC 8693 token exchange, macOS Keychain |

---

## `$ kubectl get pods --homelab`

```
NAME                          READY   STATUS    RESTARTS   COMPONENT
argocd-server                 1/1     Running   0          GitOps controller
zitadel-0                     1/1     Running   0          OIDC identity provider
envoy-gateway                 1/1     Running   0          Ingress (SNI multi-tenant)
cert-manager                  1/1     Running   0          TLS automation
external-secrets              1/1     Running   0          OCI Vault integration
netbird-server                1/1     Running   0          Zero-trust VPN
cloudnativepg-cluster         3/3     Running   0          PostgreSQL HA
prometheus-stack              2/2     Running   0          Observability
harbor                        1/1     Running   0          Container registry
backstage                     1/1     Running   0          Developer portal
coder                         1/1     Running   0          Cloud dev environments
forgejo                       1/1     Running   0          Self-hosted Git
... 20 more pods running
```

> Platform: OKE (Oracle Kubernetes Engine) · GitOps: ArgoCD + Kustomize · 30+ components

---

## `$ cat /proc/github-stats`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=drtinkerer&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&rank_icon=github" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=drtinkerer&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&langs_count=8" height="165" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=drtinkerer&theme=github-compact&hide_border=true&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FFFFFF" />
</div>

---

<div align="center">

**`$ curl -s https://bhushan.dev/contact`**

[![LinkedIn](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/drtinkerer/)
[![Portfolio](https://img.shields.io/badge/cloudpoet.in-0D1117?style=for-the-badge&logo=cloudflare&logoColor=F6821F)](https://cloudpoet.in/)
[![Email](https://img.shields.io/badge/email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eulersidentity2718@gmail.com)
[![Medium](https://img.shields.io/badge/medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@drtinkerer)

<br/>

```
"The infrastructure runs in the dark, so everything else can run in the light."
```

</div>
