<div align="center">

<a href="https://github.com/agustin2505">
  <img src="https://readme-typing-svg.demolab.com/?lines=Platform+%26+Infrastructure+Engineer;Google+Cloud+%7C+Kubernetes+%7C+Terraform;Shipping+production+infra+for+financial+services;Multi-tenant+landing+zones+with+compliance&font=Fira%20Code&center=true&width=600&height=45&color=7aa2f7&vCenter=true&size=22&pause=1000" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/Location-Mendoza,%20Argentina-1f6feb?style=flat-square" alt="Location" />
<img src="https://img.shields.io/badge/Role-Platform%20Engineer-2ea043?style=flat-square" alt="Role" />
<img src="https://img.shields.io/badge/Domain-Financial%20Services-e8a33d?style=flat-square" alt="Domain" />
<img src="https://komarev.com/ghpvc/?username=agustin2505&label=Profile%20views&color=7aa2f7&style=flat-square" alt="Profile views" />

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=140&section=header&text=Agustín%20Exequiel%20Muñoz&fontSize=36&fontColor=fff&animation=fadeIn&fontAlignY=40" width="100%" />

</div>

## About me

Platform & Infrastructure Engineer building a **multi-tenant Google Cloud landing zone** for a bank in production, based on [Cloud Foundation Fabric / FAST](https://github.com/GoogleCloudPlatform/cloud-foundation-fabric). I design and operate the compute, networking, identity, and data layers — from Terraform modules to GKE clusters to CI/CD pipelines.

Currently I own the **AI / RAG platform layer**: private GKE on Shared VPC, Cloud SQL with pgvector, Apache Airflow 3, Langfuse, Workload Identity Federation for the CD pipeline, VPC Service Controls, CMEK on every data plane, Artifact Registry as the OCI chart and container registry.

CS student at **UTN-FRSR** (4th year). Based in **Mendoza, Argentina**. Comfortable in English and Spanish.

---

## Core expertise

<table>
  <tr>
    <td valign="top" width="33%">
      <h3 align="center">Cloud Platform</h3>
      <p align="center">
        <img src="https://skillicons.dev/icons?i=gcp" />
      </p>
      <p align="center">
        <sub><b>Google Cloud Platform</b>: GKE (private clusters), Cloud SQL (PostgreSQL), Cloud Storage, Artifact Registry, Secret Manager, VPC Service Controls, Shared VPC, Cloud NAT, Cloud DNS, Cloud KMS, Cloud Logging, Cloud Monitoring, IAM, Organization Policies, Workload Identity, Workload Identity Federation (WIF), Fleet / Connect Gateway</sub>
      </p>
    </td>
    <td valign="top" width="33%">
      <h3 align="center">Infrastructure as Code</h3>
      <p align="center">
        <img src="https://skillicons.dev/icons?i=terraform,bash" />
      </p>
      <p align="center">
        <sub><b>Terraform</b> (HCL): Cloud Foundation Fabric / FAST framework, multi-tenant landing zones, module design, remote state (GCS backend), environment parametrization. <b>Helm 3</b>: OCI chart distribution, hooks, values layering. <b>Shell scripting</b>: Bash, deploy automation.</sub>
      </p>
    </td>
    <td valign="top" width="33%">
      <h3 align="center">Containers & CD</h3>
      <p align="center">
        <img src="https://skillicons.dev/icons?i=kubernetes,docker,githubactions" />
      </p>
      <p align="center">
        <sub><b>Kubernetes</b>: GKE private clusters, Workload Identity, network policies, node pools with taints/tolerations, HPA, PDB. <b>Docker</b>: multi-stage builds, rootless containers, Artifact Registry. <b>GitHub Actions</b>: CD pipelines with OIDC / WIF (no static keys), matrix builds, rollback flows.</sub>
      </p>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3 align="center">Security & Compliance</h3>
      <p align="center">
        <sub><b>Identity</b>: IAM least privilege, service account impersonation, Workload Identity Federation, OIDC. <b>Network</b>: private clusters, VPC-SC perimeters, Private Google Access, authorized networks. <b>Data</b>: CMEK (Customer-Managed Encryption Keys), Secret Manager, TLS enforcement. <b>Governance</b>: Org Policies, folder-level overrides, ISO 27001, BCRA (Argentina banking compliance).</sub>
      </p>
    </td>
    <td valign="top">
      <h3 align="center">Data & Observability</h3>
      <p align="center">
        <sub><b>PostgreSQL</b> on Cloud SQL: private IP, Cloud SQL Auth Proxy, pgvector (halfvec, HNSW), Alembic migrations. <b>Redis</b> (Bitnami) for caching. <b>Apache Airflow 3</b> on GKE (Composer parity). <b>Langfuse</b> for LLM observability. <b>OpenTelemetry</b>.</sub>
      </p>
    </td>
    <td valign="top">
      <h3 align="center">Languages</h3>
      <p align="center">
        <img src="https://skillicons.dev/icons?i=python,bash" />
      </p>
      <p align="center">
        <sub><b>Python</b>: FastAPI backends, Alembic migrations, Airflow DAGs. <b>Bash</b>: deployment and bootstrap scripts. <b>HCL</b>: Terraform modules. <b>SQL</b>: PostgreSQL, query optimization.</sub>
      </p>
    </td>
  </tr>
</table>

---

## Keywords

<sub>Google Cloud Platform · GCP · Kubernetes · GKE · Terraform · HCL · Helm · Helm Charts · Cloud Foundation Fabric · FAST framework · Landing Zone · Multi-tenant · IaC · Infrastructure as Code · DevOps · Platform Engineering · SRE · Site Reliability Engineering · CI/CD · GitHub Actions · GitOps · Workload Identity Federation · WIF · OIDC · IAM · Service Accounts · Least Privilege · Cloud SQL · PostgreSQL · pgvector · Apache Airflow · Langfuse · Python · Bash · Docker · Container Orchestration · Shared VPC · VPC Service Controls · VPC-SC · Private GKE · CMEK · Secret Manager · Artifact Registry · OCI · Organization Policies · Cloud Monitoring · Cloud Logging · OpenTelemetry · Financial Services · Banking · ISO 27001 · BCRA · Compliance · RAG · LLM Infrastructure · Vertex AI</sub>

---

## What I am building

<table>
<tr>
<td valign="top" width="60%">

### [war-stories](https://github.com/agustin2505/war-stories)

Production infrastructure debugging narratives. Context, failed attempts, the aha moment, the fix. Written for engineers who hit real problems — not for tutorials.

**Featured**: [The catch-22 of Helm pre-install hooks](https://github.com/agustin2505/war-stories/blob/main/projects/banking-ai-platform/01-helm-pre-install-hook-catch-22.md) — how Helm atomic rollback interacts with externally-managed ServiceAccounts in GKE with Workload Identity.

**Coverage**: Helm, GKE, Terraform, GCP org policies, WIF multi-branch CD, Cloud SQL extensions, Airflow rollout strategies.

</td>
<td valign="top" width="40%">

<img src="https://github-readme-stats.vercel.app/api/pin/?username=agustin2505&repo=war-stories&theme=tokyonight&hide_border=true" />

</td>
</tr>
</table>

---

## GitHub activity

<div align="center">

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=agustin2505&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=agustin2505&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=agustin2505&theme=tokyonight&hide_border=true" />

</div>

---

## Contact

<p align="left">
  <a href="mailto:agussseze@gmail.com">
    <img src="https://img.shields.io/badge/Email-agussseze%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/agustin-muñoz-85b79b249/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/agustin2505">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

Open to **Platform Engineering**, **Site Reliability Engineering (SRE)**, **DevOps**, or **Cloud / Infrastructure** roles — full-time, part-time, internship, or consulting.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer" width="100%" />

</div>
