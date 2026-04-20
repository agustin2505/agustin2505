<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:000000,100:00ff41&height=180&section=header&text=%24%20whoami&fontColor=00ff41&fontSize=50&fontAlignY=55&desc=agustin2505%20//%20platform%20%26%20infrastructure%20engineer&descAlignY=80&descSize=14&descAlign=50&animation=fadeIn" width="100%" />

<a href="https://github.com/agustin2505">
  <img src="https://readme-typing-svg.demolab.com/?lines=%24+uname+-r+platform-engineer;%24+whoami+%E2%86%92+agustin2505;%24+cat+stack.txt+%E2%86%92+gcp+k8s+terraform;%24+grep+-r+%22production%22+%2Finfra;%24+systemctl+status+landing-zone.service+%E2%9C%93&font=Fira%20Code&center=true&width=720&height=50&color=00ff41&vCenter=true&size=20&pause=1200&cursor=true" alt="Typing" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/LOC-Mendoza_%7C_AR-00ff41?style=flat-square&labelColor=0d1117&color=00ff41" />
<img src="https://img.shields.io/badge/ROLE-Platform_Engineer-00ff41?style=flat-square&labelColor=0d1117&color=00ff41" />
<img src="https://img.shields.io/badge/DOMAIN-Financial_Services-00ff41?style=flat-square&labelColor=0d1117&color=00ff41" />
<img src="https://img.shields.io/badge/STATUS-Online-00ff41?style=flat-square&labelColor=0d1117&color=00ff41" />
<img src="https://komarev.com/ghpvc/?username=agustin2505&label=VISITORS&color=00ff41&style=flat-square&labelColor=0d1117" />

</div>

---

```bash
┌──(agustin㉿infra)-[~]
└─$ cat ./profile.yaml
```

```yaml
identity:
  name:       "Agustín Exequiel Muñoz"
  role:       "Platform & Infrastructure Engineer"
  location:   "Mendoza, Argentina"
  education:  "UTN-FRSR · CS · 4th year"
  languages:  [es_AR, en_US]

currently_building:
  target:     "Multi-tenant GCP landing zone for a bank (production)"
  framework:  "Cloud Foundation Fabric / FAST"
  owning:     "AI / RAG platform layer — GKE + Cloud SQL pgvector + Airflow 3"
  principles: [least-privilege, zero-static-keys, cmek-everywhere, vpc-sc]

status:       "open_to_opportunities"
```

<div align="center">

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOXR5ZGx6a2hqdXB2aXJ3aW05aXhpaWY2cWR1Z3QwZGdjN3MxcnhkeCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/eKu42vbTZFvKw/giphy.gif" width="100%" height="200" />

</div>

---

## `// core_stack`

<table>
  <tr>
    <td valign="top" width="33%">
      <h3 align="center"><code>[ cloud ]</code></h3>
      <p align="center"><img src="https://skillicons.dev/icons?i=gcp" /></p>
      <p align="center">
        <sub><b>GCP</b>: GKE (private), Cloud SQL (pgvector), GCS, Artifact Registry, Secret Manager, <b>VPC-SC</b>, Shared VPC, Cloud NAT/DNS, <b>KMS (CMEK)</b>, IAM, Org Policies, <b>WIF</b>, Fleet / Connect Gateway</sub>
      </p>
    </td>
    <td valign="top" width="33%">
      <h3 align="center"><code>[ iac ]</code></h3>
      <p align="center"><img src="https://skillicons.dev/icons?i=terraform,bash" /></p>
      <p align="center">
        <sub><b>Terraform / HCL</b>: Cloud Foundation Fabric, FAST v52+, multi-tenant landing zones, module design, GCS remote state. <b>Helm 3</b>: OCI charts, hooks, values layering. <b>Bash</b>: deploy automation.</sub>
      </p>
    </td>
    <td valign="top" width="33%">
      <h3 align="center"><code>[ runtime ]</code></h3>
      <p align="center"><img src="https://skillicons.dev/icons?i=kubernetes,docker,githubactions" /></p>
      <p align="center">
        <sub><b>Kubernetes</b>: private GKE, Workload Identity, NetworkPolicies, taints/tolerations, HPA, PDB. <b>Docker</b>: multi-stage, rootless. <b>GitHub Actions</b>: CD via <b>OIDC/WIF — no static keys</b>, matrix builds.</sub>
      </p>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3 align="center"><code>[ security ]</code></h3>
      <p align="center">
        <sub><b>Identity</b>: SA impersonation, WIF, OIDC, least privilege. <b>Network</b>: private clusters, VPC-SC perimeters, Private Google Access, authorized networks. <b>Data</b>: <b>CMEK</b>, Secret Manager, TLS enforcement. <b>Governance</b>: folder-level Org Policy overrides, <b>ISO 27001</b>, <b>BCRA</b>.</sub>
      </p>
    </td>
    <td valign="top">
      <h3 align="center"><code>[ data / obs ]</code></h3>
      <p align="center">
        <sub><b>PostgreSQL</b> on Cloud SQL: private IP, Auth Proxy, <b>pgvector</b> (halfvec, HNSW), Alembic. <b>Redis</b> (Bitnami). <b>Airflow 3</b> on GKE (Composer parity). <b>Langfuse</b> (LLM obs). <b>OpenTelemetry</b>.</sub>
      </p>
    </td>
    <td valign="top">
      <h3 align="center"><code>[ lang ]</code></h3>
      <p align="center"><img src="https://skillicons.dev/icons?i=python,bash" /></p>
      <p align="center">
        <sub><b>Python</b>: FastAPI, Alembic, Airflow DAGs. <b>Bash</b>: bootstrap scripts. <b>HCL</b>: Terraform modules. <b>SQL</b>: PostgreSQL, query optimization.</sub>
      </p>
    </td>
  </tr>
</table>

---

## `// field_notes`

<table>
<tr>
<td valign="top" width="60%">

### ▸ [`war-stories`](https://github.com/agustin2505/war-stories)

> Production infrastructure debugging narratives. Context, failed attempts, the aha moment, the fix. Written for engineers who hit real problems — not for tutorials.

**`[featured]`** → [The catch-22 of Helm pre-install hooks](https://github.com/agustin2505/war-stories/blob/main/projects/banking-ai-platform/01-helm-pre-install-hook-catch-22.md) — how Helm atomic rollback interacts with externally-managed ServiceAccounts in GKE with Workload Identity.

**`[coverage]`** → Helm · GKE · Terraform · GCP org policies · WIF multi-branch CD · Cloud SQL extensions · Airflow rollout · Cilium NetworkPolicy · Certificate Manager · Shared VPC NEGs.

</td>
<td valign="top" width="40%">

<a href="https://github.com/agustin2505/war-stories">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=agustin2505&repo=war-stories&theme=merko&hide_border=true&bg_color=0d1117" />
</a>

</td>
</tr>
</table>

---

## `// telemetry`

<div align="center">

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=agustin2505&show_icons=true&theme=merko&hide_border=true&bg_color=0d1117&count_private=true&include_all_commits=true&icon_color=00ff41&title_color=00ff41&text_color=00ff41" />
<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=agustin2505&layout=compact&theme=merko&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=00ff41&langs_count=8" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=agustin2505&theme=dark&hide_border=true&background=0d1117&stroke=00ff41&ring=00ff41&fire=00ff41&currStreakLabel=00ff41&sideLabels=00ff41&currStreakNum=ffffff&sideNums=ffffff&dates=888888" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=agustin2505&theme=github-compact&bg_color=0d1117&color=00ff41&line=00ff41&point=ffffff&hide_border=true&area=true" width="98%" />

</div>

---

## `// keywords`

<sub>`gcp` · `kubernetes` · `gke` · `terraform` · `hcl` · `helm` · `cloud-foundation-fabric` · `fast-framework` · `landing-zone` · `multi-tenant` · `iac` · `devops` · `platform-engineering` · `sre` · `ci-cd` · `github-actions` · `gitops` · `wif` · `oidc` · `iam` · `least-privilege` · `cloud-sql` · `postgresql` · `pgvector` · `airflow` · `langfuse` · `python` · `bash` · `docker` · `shared-vpc` · `vpc-sc` · `private-gke` · `cmek` · `secret-manager` · `artifact-registry` · `oci` · `org-policies` · `opentelemetry` · `financial-services` · `banking` · `iso-27001` · `bcra` · `compliance` · `rag` · `llm-infrastructure` · `vertex-ai`</sub>

---

## `// contact`

<p align="left">
  <a href="mailto:agussseze@gmail.com">
    <img src="https://img.shields.io/badge/MAIL-agussseze%40gmail.com-00ff41?style=for-the-badge&logo=protonmail&logoColor=00ff41&labelColor=0d1117" />
  </a>
  <a href="https://www.linkedin.com/in/agustin-muñoz-85b79b249/">
    <img src="https://img.shields.io/badge/LINKEDIN-connect-00ff41?style=for-the-badge&logo=linkedin&logoColor=00ff41&labelColor=0d1117" />
  </a>
  <a href="https://github.com/agustin2505">
    <img src="https://img.shields.io/badge/GITHUB-agustin2505-00ff41?style=for-the-badge&logo=github&logoColor=00ff41&labelColor=0d1117" />
  </a>
</p>

```bash
┌──(agustin㉿infra)-[~]
└─$ echo $AVAILABILITY
> open to: Platform Engineering · SRE · DevOps · Cloud / Infrastructure
> modes:   full-time · part-time · internship · consulting
```

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:00ff41,100:000000&height=80&section=footer" width="100%" />

<sub><code>// end of transmission</code></sub>

</div>
