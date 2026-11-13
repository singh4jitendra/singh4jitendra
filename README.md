<p align="center">
  <img src="./assets/profile-banner.svg" alt="Jitendra Singh | Systems, cloud, and AI infrastructure" width="100%">
</p>

<p align="center">
  <strong>From system-level code to observable, trust-aware infrastructure.</strong>
</p>

<p align="center">
  <a href="#about">About</a> &nbsp;|&nbsp;
  <a href="#languages-and-tooling">Tech stack</a> &nbsp;|&nbsp;
  <a href="#open-source-portfolio">Open source</a> &nbsp;|&nbsp;
  <a href="#research-and-projects">Projects</a> &nbsp;|&nbsp;
  <a href="#github-achievement">Achievement</a>
</p>

## About

My public work connects **systems programming, cloud storage, AI infrastructure, and confidential-computing research**. I focus on concrete engineering problems: clearer diagnostics, reliable batch tooling, tracing, storage API contracts, and trust-aware deployments.

This portfolio includes merged upstream work, active pull-request submissions, research in progress, and applied data projects. The linked repositories and pull requests provide implementation details and current status.

## Languages and tooling

**Code**

<p>
  <img src="https://img.shields.io/badge/Go-0B7897?style=for-the-badge&amp;logo=go&amp;logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Rust-1F2328?style=for-the-badge&amp;logo=rust&amp;logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/C-3949AB?style=for-the-badge&amp;logo=c&amp;logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&amp;logo=cplusplus&amp;logoColor=white" alt="C++">
</p>

**Infrastructure, research, and data**

<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&amp;logo=kubernetes&amp;logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Argo_CD-DF4B2B?style=for-the-badge&amp;logo=argo&amp;logoColor=white" alt="Argo CD">
  <img src="https://img.shields.io/badge/Prometheus-BE3D22?style=for-the-badge&amp;logo=prometheus&amp;logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/Git-C13D23?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Jupyter-A95800?style=for-the-badge&amp;logo=jupyter&amp;logoColor=white" alt="Jupyter">
</p>

| Area | Public work |
| --- | --- |
| Cloud storage and observability | Go, GCSFuse, Prometheus, and operator-facing diagnostics. |
| AI infrastructure | Python submissions for PyTorch custom operators and vLLM batch tooling. |
| Container tracing | Rust submission for agent trace export in Kata Containers. |
| Storage APIs | Protocol Buffers and Go submissions covering request identity and response boundaries. |
| Trusted deployments | Kubernetes, Argo CD, Confidential Containers, and remote-attestation research. |
| Applied machine learning | Python notebooks, regression modeling, and exploratory data analysis. |

## Open-source portfolio

Selected upstream contributions and submissions. **The badges show live PR status; an open submission is not a merged contribution.**

| Project | Selected contribution | Live status |
| --- | --- | --- |
| [GCSFuse](https://github.com/GoogleCloudPlatform/gcsfuse) | [Accurate Prometheus metrics-listener logging](https://github.com/GoogleCloudPlatform/gcsfuse/pull/5229) | [![GCSFuse pull request status](https://img.shields.io/github/pulls/detail/state/GoogleCloudPlatform/gcsfuse/5229?style=flat-square&label=PR%20%235229)](https://github.com/GoogleCloudPlatform/gcsfuse/pull/5229) |
| [PyTorch](https://github.com/pytorch/pytorch) | [Tuple input annotations for custom operators](https://github.com/pytorch/pytorch/pull/204556) | [![PyTorch pull request status](https://img.shields.io/github/pulls/detail/state/pytorch/pytorch/204556?style=flat-square&label=PR%20%23204556)](https://github.com/pytorch/pytorch/pull/204556) |
| [vLLM](https://github.com/vllm-project/vllm) | [Opt-in completion-order output for batch inference](https://github.com/vllm-project/vllm/pull/65670) | [![vLLM pull request status](https://img.shields.io/github/pulls/detail/state/vllm-project/vllm/65670?style=flat-square&label=PR%20%2365670)](https://github.com/vllm-project/vllm/pull/65670) |
| [Kata Containers](https://github.com/kata-containers/kata-containers) | [Agent trace export and OTLP forwarding](https://github.com/kata-containers/kata-containers/pull/14238) | [![Kata Containers pull request status](https://img.shields.io/github/pulls/detail/state/kata-containers/kata-containers/14238?style=flat-square&label=PR%20%2314238)](https://github.com/kata-containers/kata-containers/pull/14238) |
| [OPI API](https://github.com/opiproject/opi-api) | [Request identity contracts for storage Create APIs](https://github.com/opiproject/opi-api/pull/508) | [![OPI API pull request status](https://img.shields.io/github/pulls/detail/state/opiproject/opi-api/508?style=flat-square&label=PR%20%23508)](https://github.com/opiproject/opi-api/pull/508) |
| [OPI SPDK Bridge](https://github.com/opiproject/opi-spdk-bridge) | [Secret redaction at client-response boundaries](https://github.com/opiproject/opi-spdk-bridge/pull/896) | [![OPI SPDK Bridge pull request status](https://img.shields.io/github/pulls/detail/state/opiproject/opi-spdk-bridge/896?style=flat-square&label=PR%20%23896)](https://github.com/opiproject/opi-spdk-bridge/pull/896) |

**Merged highlight:** the GCSFuse change aligns Prometheus startup logs with the actual listener address, improving operational clarity without changing listener or scraping behavior. [Read the change and its validation](https://github.com/GoogleCloudPlatform/gcsfuse/pull/5229).

## Research and projects

### Zero-Trust GitOps

[Attestation-aware deployments with Argo CD and Confidential Containers](https://github.com/singh4jitendra/Zero-Trust-GitOps).

Research exploring how remote attestation and confidential-computing environments can inform deployment trust decisions in a GitOps workflow.

**Status:** research in progress. The public repository currently describes the proposed approach; the full implementation is not yet public.

### Applied data projects

| Project | Focus |
| --- | --- |
| [Car Price Modeling](https://github.com/singh4jitendra/Predict_Car_Price) | Multiple linear regression to study the factors affecting car prices. |
| [Loan Default Analysis](https://github.com/singh4jitendra/Predict_Loan_Defaulter) | Historical loan-applicant analysis to identify patterns associated with default risk. |
| [Investment Analysis](https://github.com/singh4jitendra/Investment-Analysis) | Comparing sectors, countries, and investment types against a defined investment brief. |

### Systems foundations

Learning projects include [C memory-allocation experiments](https://github.com/singh4jitendra/OWN_MALLOC) using `sbrk`, `mmap`, and `munmap`, alongside [C++ coding practice](https://github.com/singh4jitendra/Coding-Practice).

## GitHub achievement

<p align="center">
  <a href="https://github.com/singh4jitendra?achievement=arctic-code-vault-contributor&amp;tab=achievements">
    <img src="https://github.githubassets.com/assets/arctic-code-vault-contributor-default-df8d74122a06.png" alt="Earned GitHub achievement: Arctic Code Vault Contributor" width="110" height="110">
  </a>
  <br>
  <strong>Arctic Code Vault Contributor</strong>
  <br>
  <a href="https://github.com/singh4jitendra?tab=achievements">View my public GitHub achievements</a>
</p>

## Current interests

- Observability that accurately reflects runtime behavior.
- Storage API contracts, predictable retries, and clear response boundaries.
- Attestation-aware deployment workflows and confidential workloads.
- Practical systems programming and interpretable data analysis.

---

<p align="center">
  <a href="https://github.com/singh4jitendra?tab=repositories"><strong>Explore my repositories</strong></a>
  &nbsp;|&nbsp;
  <a href="https://github.com/search?q=author%3Asingh4jitendra%20is%3Apr&amp;type=pullrequests">Follow my upstream work</a>
</p>
