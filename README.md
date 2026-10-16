# Hi, I'm Yiping Deng 👋

**Tech Lead, AI Data @ [HubSpot](https://www.hubspot.com)** · Dublin, Ireland

I build the data platforms behind AI: distributed data systems, vector search, GPU infrastructure, and AI observability.

[![Website](https://img.shields.io/badge/loudcoder.com-000?style=flat&logo=googlechrome&logoColor=white)](https://loudcoder.com)
[![CV](https://img.shields.io/badge/CV-PDF-000?style=flat&logo=readthedocs&logoColor=white)](https://loudcoder.com/downloads/Yiping_Deng_Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000?style=flat)](https://www.linkedin.com/in/yipingdeng/)
[![Email](https://img.shields.io/badge/Email-000?style=flat&logo=gmail&logoColor=white)](mailto:yiping.deng.98@gmail.com)

## What I work on

- **Data platforms**: I own and modernize Spark infrastructure, help build Apache Iceberg infrastructure, and make the cost of a $6-7M/year Spark fleet visible.
- **AI infrastructure**: vector search for RAG and semantic search at 7B+ production ANN vectors across 200+ indices, plus inference and feedback pipelines that ingest 2 TB/day.
- **Observable AI systems**: OpenTelemetry tracing and storage covering every AI agent at HubSpot, and AI agents that analyze data-entity lineage graphs.

| 7B+ | 80% | 2 TB/day | $90K to $5K |
| :---: | :---: | :---: | :---: |
| production ANN vectors | less Spark support load with AI-agent job auto-tuning | AI inference and feedback ingested | monthly storage cost after migrating off HBase |

## Open source

- **[Qdrant](https://github.com/qdrant/qdrant/pulls?q=is%3Apr+is%3Amerged+author%3ADengYiping)**: peer-to-peer [mutual TLS](https://github.com/qdrant/qdrant/pull/1642), [client certificate validation](https://github.com/qdrant/qdrant/pull/1663), [live TLS certificate rotation](https://github.com/qdrant/qdrant/pull/1808), and [cluster-mode regression tests](https://github.com/qdrant/qdrant/pull/2442).
- **[Apache Spark](https://github.com/apache/spark/pull/58996)** (in review): don't retry compaction of rolled event log files with malformed input.
- Smaller fixes in [unsloth-zoo](https://github.com/unslothai/unsloth-zoo/pull/177), [OpenMetadata](https://github.com/open-metadata/OpenMetadata/pull/25938), and [jean](https://github.com/coollabsio/jean/pull/183).

## Recent projects

| Project | What it does |
| --- | --- |
| [CLIProxyAPI plugins](https://github.com/DengYiping?tab=repositories&q=cliproxyapi) | Go and Python plugins for Codex Responses compatibility, remote compaction, web-search redirection, and Kimi reasoning prefill |
| [codebase-ai-prompt-generator](https://github.com/DengYiping/codebase-ai-prompt-generator) | CLI that turns an entire codebase into a prompt for long-context LLMs |
| [codex-tool-mock](https://github.com/DengYiping/codex-tool-mock) | Mock Codex tools to test and evaluate skills |
| [learning-cuda](https://github.com/DengYiping/learning-cuda) | Notebooks from working through CUDA |
| [parquet-cat](https://github.com/DengYiping/parquet-cat) | Rust CLI to explore Parquet files and folders on S3 |

## Writing

- [Hilbert's tenth: from machines to equations, and a new rational-case claim](https://loudcoder.com/blog/hilberts-tenth-from-machines-to-rationals/)
- [Hilbert Meets Isabelle: Formalisation of the DPRM Theorem in Isabelle](https://easychair.org/publications/preprint/GhvC) (co-author, EasyChair Preprint 152)
- More on [loudcoder.com/blog](https://loudcoder.com/blog/)

## Toolbox

![Python](https://img.shields.io/badge/Python-000?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-000?style=flat&logo=openjdk&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-000?style=flat&logo=scala&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000?style=flat&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-000?style=flat&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-000?style=flat&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-000?style=flat&logo=nvidia&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-000?style=flat&logo=pytorch&logoColor=white)
<br>
![Apache Spark](https://img.shields.io/badge/Apache_Spark-000?style=flat&logo=apachespark&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache_Iceberg-000?style=flat&logo=apache&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-000?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-000?style=flat)
![Snowflake](https://img.shields.io/badge/Snowflake-000?style=flat&logo=snowflake&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-000?style=flat&logo=qdrant&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000?style=flat&logo=opentelemetry&logoColor=white)
![JupyterHub](https://img.shields.io/badge/JupyterHub-000?style=flat&logo=jupyter&logoColor=white)

💬 Ask me about Spark, Iceberg, vector search, CUDA, or LLM infrastructure. Always happy to collaborate on AI infra tooling and big data systems.
