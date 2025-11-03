# Complete Exercise Index

> **Comprehensive catalog of all hands-on exercises in the AI Infrastructure Engineer curriculum**

This document provides a complete index of all exercises across the 10-module curriculum, including time estimates, prerequisites, and solution availability.

## Overview

- **Total Modules**: 10 (mod-101 through mod-110)
- **Total Exercises**: 24+ documented exercises
- **Total Exercise Time**: 651-825+ hours
- **Solution Coverage**: 100% for advanced exercises

---

## Table of Contents

- [Module 101: Foundations](#module-101-foundations)
- [Module 104: Kubernetes](#module-104-kubernetes)
- [Module 105: Data Pipelines](#module-105-data-pipelines)
- [Module 106: MLOps](#module-106-mlops)
- [Module 107: GPU Computing](#module-107-gpu-computing)
- [Module 108: Monitoring & Observability](#module-108-monitoring--observability)
- [Module 109: Infrastructure as Code](#module-109-infrastructure-as-code)
- [Module 110: LLM Infrastructure](#module-110-llm-infrastructure)
- [Summary Statistics](#summary-statistics)

---

## Module 101: Foundations

**Location**: `lessons/mod-101-foundations/exercises/`
**Total Exercises**: 7 (4 foundational + 3 advanced)
**Total Time**: 100-123 hours

### Foundational Exercises (Lesson-Aligned)

| # | Exercise | Type | Time | Solution | Description |
|---|----------|------|------|----------|-------------|
| 01 | Environment Setup | Markdown | 2-3 hrs | ❌ | Python setup, virtual environments, dependency management |
| 02 | Docker Fundamentals | Markdown | 2-3 hrs | ❌ | Docker installation, containerization basics, Dockerfile |
| 03 | Kubernetes Deployment | Markdown | 3-4 hrs | ❌ | Minikube setup, basic deployments, services |
| 07 | FastAPI ML Service | Markdown | 4-5 hrs | ❌ | Production FastAPI app with ML inference, testing, Docker |

**Subtotal**: 12-15 hours

### Advanced Projects

| # | Exercise | Type | Time | Solution | Description |
|---|----------|------|------|----------|-------------|
| 04 | Python Environment Manager | Directory | 30-38 hrs | ✅ | CLI tool for managing Python environments with uv/conda/poetry |
| 05 | ML Framework Benchmarking | Directory | 31-40 hrs | ✅ | Comprehensive ML framework performance comparison tool |
| 06 | FastAPI Template Generator | Directory | 27-34 hrs | ✅ | Production-grade FastAPI ML service template generator |

**Subtotal**: 88-108 hours

**Topics**: Python tooling, environment management, ML frameworks, PyTorch, TensorFlow, JAX, Docker, FastAPI, Pydantic, testing

**Prerequisites**: Python programming, basic ML knowledge, command-line proficiency

---

## Module 104: Kubernetes

**Location**: `lessons/mod-104-kubernetes/exercises/`
**Total Exercises**: 3 (all advanced)
**Total Time**: 105-135 hours

| # | Exercise | Type | Time | Solution | Description |
|---|----------|------|------|----------|-------------|
| 04 | K8s Cluster Autoscaler | Directory | 35-43 hrs | ✅ | HPA, VPA, Cluster Autoscaler, node pools, cost optimization |
| 05 | Service Mesh Observability | Directory | 35-45 hrs | ✅ | Istio/Linkerd deployment, distributed tracing, service graphs |
| 06 | K8s Operator Framework | Directory | 35-45 hrs | ✅ | Custom operators with SDK, CRDs, reconciliation loops |

**Topics**: Kubernetes autoscaling, service mesh, Istio, Linkerd, operators, CRDs, webhooks, RBAC

**Prerequisites**: Module 104 lessons, Kubernetes fundamentals, understanding of distributed systems

---

## Module 105: Data Pipelines

**Location**: `lessons/mod-105-data-pipelines/exercises/`
**Total Exercises**: 2 (all advanced)
**Total Time**: 71-89 hours

| # | Exercise | Type | Time | Solution | Description |
|---|----------|------|------|----------|-------------|
| 03 | Real-Time Feature Pipeline | Directory | 36-44 hrs | ✅ | Kafka Streams, real-time feature computation, stream processing |
| 04 | Workflow Orchestration | Directory | 35-45 hrs | ✅ | Airflow DAGs, data lineage, ML pipeline orchestration |

**Topics**: Apache Kafka, Kafka Streams, Apache Flink, Apache Airflow, DVC, MLflow, streaming data, batch processing

**Prerequisites**: Module 105 lessons, data engineering concepts, understanding of distributed systems

---

## Module 106: MLOps

**Location**: `lessons/mod-106-mlops/exercises/`
**Total Exercises**: 3 (all advanced)
**Total Time**: 90-118 hours

| # | Exercise | Type | Time | Solution | Description |
|---|----------|------|------|----------|-------------|
| 04 | Experiment Tracking | Directory | 30-38 hrs | ✅ | MLflow deployment, experiment tracking, model registry |
| 05 | Model Monitoring & Drift | Directory | 30-40 hrs | ✅ | Data drift detection, model performance monitoring, alerting |
| 06 | CI/CD for ML Pipelines | Directory | 30-40 hrs | ✅ | Automated testing, model validation, deployment automation |

**Topics**: MLflow, experiment tracking, model registry, Evidently, WhyLabs, data drift, model drift, CI/CD, GitHub Actions

**Prerequisites**: Module 106 lessons, ML model training experience, understanding of DevOps practices

---

## Module 107: GPU Computing

**Location**: `lessons/mod-107-gpu-computing/exercises/`
**Total Exercises**: 3 (all advanced)
**Total Time**: 105-135 hours

| # | Exercise | Type | Time | Solution | Description |
|---|----------|------|------|----------|-------------|
| 04 | GPU Cluster Management | Directory | 35-45 hrs | ✅ | Multi-node GPU setup, SLURM/K8s scheduling, resource allocation |
| 05 | GPU Performance Optimization | Directory | 35-45 hrs | ✅ | CUDA profiling, kernel optimization, mixed precision training |
| 06 | Distributed GPU Training | Directory | 35-45 hrs | ✅ | Data/model/pipeline parallelism, ZeRO optimizer, NCCL |

**Topics**: CUDA, GPU clusters, SLURM, Kubernetes GPU Operator, Nsight, PyTorch DDP, Horovod, DeepSpeed, distributed training

**Prerequisites**: Module 107 lessons, GPU access, CUDA basics, distributed systems knowledge

---

## Module 108: Monitoring & Observability

**Location**: `lessons/mod-108-monitoring-observability/exercises/`
**Total Exercises**: 2 (all advanced)
**Total Time**: 56-72 hours

| # | Exercise | Type | Time | Solution | Description |
|---|----------|------|------|----------|-------------|
| 01 | Observability Stack | Directory | 28-36 hrs | ✅ | Prometheus, Grafana, Loki, AlertManager, full observability |
| 02 | ML Model Monitoring | Directory | 28-36 hrs | ✅ | Model performance tracking, custom ML metrics, drift detection |

**Topics**: Prometheus, Grafana, Loki, AlertManager, observability, metrics, logs, dashboards, ML monitoring

**Prerequisites**: Module 108 lessons, Docker, Kubernetes, understanding of monitoring concepts

---

## Module 109: Infrastructure as Code

**Location**: `lessons/mod-109-infrastructure-as-code/exercises/`
**Total Exercises**: 2 (all advanced)
**Total Time**: 64-80 hours

| # | Exercise | Type | Time | Solution | Description |
|---|----------|------|------|----------|-------------|
| 01 | Terraform ML Infrastructure | Directory | 32-40 hrs | ✅ | Complete ML infrastructure: VPC, EKS/GKE, GPU nodes, monitoring |
| 02 | Pulumi Multi-Cloud | Directory | 32-40 hrs | ✅ | Multi-cloud deployment with Python/TypeScript, disaster recovery |

**Topics**: Terraform, Pulumi, Infrastructure as Code, AWS, GCP, Azure, multi-cloud, Vault, secrets management

**Prerequisites**: Module 109 lessons, Terraform basics, cloud platform access, programming knowledge

---

## Module 110: LLM Infrastructure

**Location**: `lessons/mod-110-llm-infrastructure/exercises/`
**Total Exercises**: 2 (all advanced)
**Total Time**: 72-88 hours

| # | Exercise | Type | Time | Solution | Description |
|---|----------|------|------|----------|-------------|
| 01 | Production LLM Serving | Directory | 36-44 hrs | ✅ | vLLM deployment, quantization, GPU optimization, autoscaling |
| 02 | Production RAG System | Directory | 36-44 hrs | ✅ | Document ingestion, embeddings, vector DBs, hybrid search, RAG |

**Topics**: vLLM, LLM serving, quantization, RAG, LangChain, vector databases (Pinecone, Weaviate, Qdrant), embeddings

**Prerequisites**: Module 110 lessons, GPU access, Kubernetes knowledge, understanding of LLMs

---

## Summary Statistics

### Exercise Distribution

| Module | Foundational | Advanced | Total | Time Range |
|--------|--------------|----------|-------|------------|
| 101 | 4 | 3 | 7 | 100-123 hrs |
| 104 | 0 | 3 | 3 | 105-135 hrs |
| 105 | 0 | 2 | 2 | 71-89 hrs |
| 106 | 0 | 3 | 3 | 90-118 hrs |
| 107 | 0 | 3 | 3 | 105-135 hrs |
| 108 | 0 | 2 | 2 | 56-72 hrs |
| 109 | 0 | 2 | 2 | 64-80 hrs |
| 110 | 0 | 2 | 2 | 72-88 hrs |
| **Total** | **4** | **20** | **24** | **663-840 hrs** |

### Solution Coverage

| Category | Exercises | Solutions Available | Coverage |
|----------|-----------|---------------------|----------|
| Foundational (Module 101) | 4 | 0 | 0% |
| Advanced (Module 101) | 3 | 3 | 100% |
| Advanced (Modules 104-110) | 17 | 17 | 100% |
| **Total** | **24** | **20** | **83%** |

**Note**: Foundational exercises (Module 101) are markdown-based with inline guidance and may not require full coded solutions.

### Technology Coverage

**Most Practiced Technologies:**
- Kubernetes (18 exercises)
- Docker (17 exercises)
- Python (24 exercises)
- Prometheus & Grafana (14 exercises)
- PostgreSQL (8 exercises)
- Apache Kafka (4 exercises)
- GPU Computing (6 exercises)
- Terraform/Pulumi (4 exercises)
- LLM Infrastructure (4 exercises)

### Time Investment by Category

| Category | Time Range |
|----------|------------|
| Foundational Exercises | 12-15 hours |
| Module 101 Advanced | 88-108 hours |
| Kubernetes (104) | 105-135 hours |
| Data Pipelines (105) | 71-89 hours |
| MLOps (106) | 90-118 hours |
| GPU Computing (107) | 105-135 hours |
| Monitoring (108) | 56-72 hours |
| IaC (109) | 64-80 hours |
| LLM Infrastructure (110) | 72-88 hours |
| **Total** | **663-840 hours** |

---

## Exercise Types Explained

### Foundational Exercises (Markdown)

**Format**: `.md` files with step-by-step instructions
**Purpose**: Guide learners through basic setup and configuration
**Time**: 2-5 hours each
**Solution**: Inline guidance provided, full solutions may not be necessary

**Example**: `exercise-01-environment.md`
- Detailed instructions for each step
- Expected outputs documented
- Troubleshooting tips included
- Success criteria clearly defined

### Advanced Exercises (Directories)

**Format**: Complete directory structures with README, starter code, tests
**Purpose**: Build production-grade systems demonstrating mastery
**Time**: 28-45 hours each
**Solution**: Full implementations available in solutions repository

**Example**: `exercise-04-gpu-cluster-management/`
```
exercise-04-gpu-cluster-management/
├── README.md                 # Exercise description and requirements
├── src/                      # Source code stubs with TODOs
├── kubernetes/               # K8s manifests
├── tests/                    # Test suites
├── docs/                     # Architecture diagrams
└── scripts/                  # Setup and deployment scripts
```

---

## How to Use This Index

### For Learners

1. **Follow the progression**: Start with foundational exercises before advanced
2. **Check prerequisites**: Ensure you've completed required modules
3. **Allocate time**: Advanced exercises require significant time investment
4. **Use solutions wisely**: Try implementing first, then compare with solutions

### For Instructors

1. **Plan curriculum**: Use time estimates for course planning
2. **Assign progressively**: Foundational → Advanced progression
3. **Grade with rubrics**: Solutions provide grading criteria
4. **Customize exercises**: Adapt based on student needs

### For Self-Study

1. **Set realistic expectations**: Advanced exercises take 30-45 hours each
2. **Block dedicated time**: Don't underestimate time requirements
3. **Document your work**: Create portfolio pieces from exercises
4. **Seek help when stuck**: Use community resources and documentation

---

## Solution Availability

### Complete Solutions Available

All 20 advanced exercises have complete, production-ready solutions in the [solutions repository](../../../solutions/ai-infra-engineer-solutions/):

**Access solutions:**
```bash
cd ../../solutions/ai-infra-engineer-solutions/
cd modules/mod-107-gpu-computing/exercise-04-gpu-cluster-management/
```

**Solution contents:**
- ✅ Complete source code (no stubs)
- ✅ Comprehensive tests
- ✅ Kubernetes manifests
- ✅ Docker configurations
- ✅ Monitoring setup
- ✅ Architecture documentation
- ✅ Deployment scripts

**Solution mapping**: See [EXERCISE_SOLUTIONS_MAP.md](../../../solutions/ai-infra-engineer-solutions/EXERCISE_SOLUTIONS_MAP.md) for detailed cross-reference.

### Missing Solutions

Module 101 foundational exercises (4 exercises, 12-15 hours total):
- exercise-01-environment.md
- exercise-02-docker.md
- exercise-03-kubernetes.md
- exercise-07-api.md

**Impact**: Low - these exercises have inline step-by-step guidance

---

## Exercise Difficulty Levels

### Beginner (Foundational)
- **Time**: 2-5 hours
- **Prerequisites**: Basic programming, command-line familiarity
- **Examples**: Module 101 foundational exercises
- **Characteristics**: Step-by-step guidance, well-defined scope, limited complexity

### Intermediate (Early Advanced)
- **Time**: 28-38 hours
- **Prerequisites**: Completed relevant module lessons, hands-on experience
- **Examples**: MLOps experiments (Exercise 04), Monitoring stack (Exercise 01)
- **Characteristics**: Production patterns, testing required, moderate complexity

### Advanced (Late Advanced)
- **Time**: 35-45 hours
- **Prerequisites**: Multiple modules completed, production experience helpful
- **Examples**: GPU clusters (Exercise 04), K8s operators (Exercise 06), LLM serving (Exercise 01)
- **Characteristics**: Complex systems, multiple integrations, production-grade requirements

---

## Recommended Learning Paths

### Path 1: Full Sequential (Comprehensive)
1. Complete all Module 101 exercises (foundational + advanced)
2. Progress through modules 104-110 in order
3. Complete all advanced exercises for each module
4. **Total time**: 663-840 hours

### Path 2: Foundations + Selected Advanced (Targeted)
1. Complete Module 101 foundational exercises
2. Select 2-3 advanced exercises from areas of interest
3. Focus on depth in chosen specialization
4. **Total time**: 150-250 hours

### Path 3: Advanced Only (Experienced Engineers)
1. Skip foundational if experienced with basics
2. Complete all 20 advanced exercises
3. Focus on production patterns and best practices
4. **Total time**: 651-825 hours

---

## Contributing

Found an issue or want to improve an exercise?

1. **Check the exercise README** for specific requirements
2. **Submit issues** for bugs or unclear instructions
3. **Propose improvements** via pull requests
4. **Share solutions** if you've implemented alternatives

---

## Additional Resources

- **[Solutions Repository](../../../solutions/ai-infra-engineer-solutions/)** - Complete exercise implementations
- **[Exercise Solutions Map](../../../solutions/ai-infra-engineer-solutions/EXERCISE_SOLUTIONS_MAP.md)** - Detailed cross-reference
- **[Main README](./README.md)** - Curriculum overview
- **[Getting Started Guide](./GETTING_STARTED.md)** - Setup instructions

---

**Last Updated**: October 31, 2025
**Maintained By**: AI Infrastructure Curriculum Team
**Version**: 1.0.0

**Questions?** Open an issue or contact ai-infra-curriculum@joshua-ferguson.com
