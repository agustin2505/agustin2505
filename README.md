<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:003b00,100:00ff41&height=180&section=header&text=%24%20whoami&fontColor=00ff41&fontSize=60&fontAlignY=42&animation=fadeIn" width="100%" />

<sub><code>agustin2505 // cloud security engineer · offensive security in progress</code></sub>

<a href="https://github.com/agustin2505">
  <img src="https://readme-typing-svg.demolab.com/?lines=%24+whoami+%E2%86%92+cloud+security+engineer;%24+cat+stack.txt+%E2%86%92+gcp+k8s+terraform;%24+grep+-r+%22least-privilege%22+%2Finfra;%24+nmap+-sV+production.landing-zone;%24+hydra+-l+admin+-P+rockyou.txt+localhost;%24+systemctl+status+defense-in-depth.service+%E2%9C%93&font=Fira%20Code&center=true&width=760&height=50&color=00ff41&vCenter=true&size=20&pause=1200&cursor=true" alt="Typing" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/LOC-Mendoza_%7C_AR-00ff41?style=flat-square&labelColor=0d1117&color=00ff41" />
<img src="https://img.shields.io/badge/ROLE-Cloud_Security_Engineer-00ff41?style=flat-square&labelColor=0d1117&color=00ff41" />
<img src="https://img.shields.io/badge/DOMAIN-Financial_Services-00ff41?style=flat-square&labelColor=0d1117&color=00ff41" />
<img src="https://img.shields.io/badge/FOCUS-Offensive_Sec_in_Progress-ff0040?style=flat-square&labelColor=0d1117&color=ff0040" />
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
  role:       "Cloud Security Engineer"
  focus:      "GCP · Kubernetes · Offensive Security (in progress)"
  location:   "Mendoza, Argentina"
  education:  "UTN-FRSR · CS · 4th year"
  languages:  [es_AR, en_US]

currently_building:
  target:     "Multi-tenant GCP landing zone for a bank (production)"
  framework:  "Cloud Foundation Fabric / FAST"
  owning:     "Security perimeter — VPC-SC, CMEK, WIF, IAM, org policies"
  principles: [least-privilege, zero-static-keys, defense-in-depth, zero-trust]

learning:
  offensive:  [pentesting, red-team, web-app-security, network-recon]
  toolkit:    [nmap, burp-suite, metasploit, wireshark, tryhackme, hackthebox]
  goal:       "Bridge blue-team infra design with red-team adversarial thinking"

status:       "open_to_opportunities"
```

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212750996-cd1b3043-0310-4c05-9e20-8e5a8e02c4ca.gif" width="100%" height="220" />

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
      <h3 align="center"><code>[ security / defense ]</code></h3>
      <p align="center">
        <sub><b>Identity</b>: SA impersonation, WIF, OIDC, least privilege. <b>Network</b>: private clusters, <b>VPC-SC</b> perimeters, Private Google Access, authorized networks. <b>Data</b>: <b>CMEK</b>, Secret Manager, TLS enforcement. <b>Governance</b>: Org Policy overrides, <b>ISO 27001</b>, <b>BCRA</b>. <b>Offensive (learning)</b>: nmap, Burp, Metasploit, Wireshark, TryHackMe, HackTheBox.</sub>
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

<sub>`cloud-security` · `devsecops` · `gcp-security` · `gcp` · `kubernetes` · `gke` · `terraform` · `hcl` · `helm` · `cloud-foundation-fabric` · `fast-framework` · `landing-zone` · `multi-tenant` · `iac` · `platform-engineering` · `sre` · `ci-cd` · `github-actions` · `gitops` · `wif` · `oidc` · `iam` · `least-privilege` · `zero-trust` · `defense-in-depth` · `cloud-sql` · `postgresql` · `pgvector` · `airflow` · `langfuse` · `python` · `bash` · `docker` · `shared-vpc` · `vpc-sc` · `private-gke` · `cmek` · `secret-manager` · `artifact-registry` · `oci` · `org-policies` · `opentelemetry` · `financial-services` · `banking` · `iso-27001` · `bcra` · `compliance` · `rag` · `llm-infrastructure` · `ethical-hacking` · `pentesting` · `offensive-security` · `red-team` · `blue-team` · `nmap` · `burp-suite` · `metasploit` · `tryhackme` · `hackthebox`</sub>

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
> open to: Cloud Security · DevSecOps · Platform Engineering · SRE · Infra
> modes:   full-time · part-time · internship · consulting
```

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:00ff41,100:000000&height=80&section=footer" width="100%" />

<sub><code>// end of transmission</code></sub>

</div>
