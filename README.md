# Awesome Cloud Native

A curated list of awesome resources around the Cloud Native landscape. ⭐

## Table of Contents

- [General Resources](#general-resources)
- [Containerization](#containerization)
- [Orchestration](#orchestration)
- [Microservices](#microservices)
- [Service Mesh](#service-mesh)
- [Immutable Infrastructure](#immutable-infrastructure)
- [DevOps Practices](#devops-practices)
- [Cloud Providers](#cloud-providers)
- [Observability and Monitoring](#observability-and-monitoring)
- [Serverless](#serverless)
- [CI/CD](#cicd)
- [WebAssembly](#webassembly)
- [Security and Governance](#security-and-governance)
- [Experimental Projects](#experimental-projects)

## General Resources

- [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/) - The foundation behind Cloud Native ecosystem.
- [Cloud Native Landscape](https://landscape.cncf.io/) - An interactive landscape of cloud native technologies.
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) - A curated list of awesome Kubernetes resources.

## Containerization

- [Docker](https://www.docker.com/) - Leading platform for containerization.
- [rkt](https://github.com/rkt/rkt) - Pod-native container engine, predates Docker in Kubernetes use.
- [containerd](https://containerd.io/) - A high-level container runtime.
- [cri-o](https://cri-o.io/) - Lightweight container runtime specifically for Kubernetes.

## Orchestration

- [Kubernetes](https://kubernetes.io/) - The de facto standard for container orchestration.
- [OpenShift](https://www.openshift.com/) - Kubernetes distribution by Red Hat with extra features.
- [Rancher](https://rancher.com/) - Complete container management platform built on Kubernetes.

## Microservices

- [Istio](https://istio.io/) - An open platform to connect, manage, and secure microservices.
- [Linkerd](https://linkerd.io/) - A service mesh for Kubernetes and other frameworks.
- [Envoy](https://www.envoyproxy.io/) - A high-performance, open-source edge and service proxy.

## Service Mesh

- [Istio](https://istio.io/) - Connects, manages, and secures microservices.
- [Linkerd](https://linkerd.io/) - Provides reliability and security to your services without requiring code changes.
- [Consul](https://www.consul.io/) - Provides a full-featured control plane with service discovery, configuration, and segmentation functionalities.

## Immutable Infrastructure

- [Packer](https://www.packer.io/) - Builds automated machine images.
- [Terraform](https://www.terraform.io/) - Provides a common configuration to launch infrastructure.
- [Ansible](https://www.ansible.com/) - IT automation tool for just about everything that runs.

## DevOps Practices

- [Jenkins](https://www.jenkins.io/) - The leading open-source automation server for CI/CD.
- [Spinnaker](https://www.spinnaker.io/) - Multi-cloud continuous delivery platform.
- [GitLab](https://about.gitlab.com/) - Complete DevOps platform, delivered as a single application.

## Cloud Providers

- [Amazon Web Services (AWS)](https://aws.amazon.com/) - Offers reliable, scalable, and inexpensive cloud computing services.
- [Google Cloud Platform (GCP)](https://cloud.google.com/) - Suite of cloud computing services alongside a set of management tools.
- [Microsoft Azure](https://azure.microsoft.com/) - Build, deploy, and manage applications across global network of datacenters.

## Observability and Monitoring

- [Prometheus](https://prometheus.io/) - Open-source systems monitoring and alerting toolkit.
- [Grafana](https://grafana.com/) - Multi-platform open source analytics and interactive visualization platform.
- [Jaeger](https://www.jaegertracing.io/) - End-to-end distributed tracing for service mesh architectures.
- [OpenTelemetry](https://opentelemetry.io/) - Provides a single set of APIs, libraries, agents, and collector services to capture distributed traces and metrics.

## Serverless

- [AWS Lambda](https://aws.amazon.com/lambda/) - Lets you run your code without provisioning or managing servers.
- [Google Cloud Functions](https://cloud.google.com/functions) - Event-driven serverless compute platform.
- [Azure Functions](https://azure.microsoft.com/services/functions/) - Develop more efficiently with Functions, an event-driven serverless compute platform.

## CI/CD

- [Jenkins](https://www.jenkins.io/) - Open-source automation tool with plugins built for continuous integration purposes.
- [CircleCI](https://circleci.com/) - Cloud-native continuous integration platform.
- [GitHub Actions](https://github.com/features/actions) - Workflow automation directly from GitHub repositories.
- [Travis CI](https://travis-ci.org/) - Hosted continuous integration service used to build and test software projects hosted on GitHub.

## WebAssembly

- [Awesome Wasm](https://github.com/mbasso/awesome-wasm) - Curated list of awesome things regarding WebAssembly ecosystem.
- [Wasmtime](https://wasmtime.dev/) - Standalone runtime for WebAssembly.
- [AssemblyScript](https://www.assemblyscript.org/) - TypeScript to WebAssembly compiler.

## Security and Governance

- [Falco](https://falco.org/) - Open source cloud native runtime security project.
- [Open Policy Agent](https://www.openpolicyagent.org/) - General-purpose policy engine.
- [KubeLinter](https://github.com/stackrox/kube-linter) - Static analysis tool checking Kubernetes YAML files and Helm charts for misconfigurations.
- [kube-score](https://github.com/zegl/kube-score) - Kubernetes object analysis with recommendations for improved reliability and security.

## Experimental Projects

### Service Mesh

- [SMI (Service Mesh Interface)](https://smi-spec.io/) - Specification for service mesh APIs.
- [Maesh](https://github.com/traefik/mesh) - Simpler Service Mesh built on top of Traefik.

### Security

- [SPIFFE](https://spiffe.io/) - Secure identity framework for production infrastructure.
- [Spire](https://spiffe.io/spire/) - Provides a unified way to issue, rotate, and revoke service identities.

### Serverless

- [OpenFaaS](https://www.openfaas.com/) - Serverless Functions Made Simple for Docker and Kubernetes.
- [Knative](https://knative.dev/) - Extending Kubernetes to build, deploy, and manage modern serverless workloads.
- [Kubeless](https://kubeless.io/) - Kubernetes-native serverless framework.

### Observability

- [Fluentd](https://www.fluentd.org/) - Open source data collector for unified logging layer.
- [Loki](https://grafana.com/oss/loki/) - Horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus.
- [Tempo](https://grafana.com/oss/tempo/) - Cost-effective, high-volume tracing system.

### Edge Computing

- [KubeEdge](https://kubeedge.io/en/) - Provides network edge computing capabilities for Kubernetes.
- [OpenYurt](https://openyurt.io/en-us/) - Extends Kubernetes to the edge.
- [K3s](https://k3s.io/) - Lightweight Kubernetes distribution perfect for edge computing.

### AI & Machine Learning

- [Kubeflow](https://www.kubeflow.org/) - Machine Learning toolkit for Kubernetes.
- [Seldon Core](https://www.seldon.io/tech/products/core/) - Open source platform for deploying machine learning models on Kubernetes.
- [Feast (Feature Store)](https://feast.dev/) - Operationalizing Machine Learning at Scale.

### GitOps

- [Flux](https://fluxcd.io/) - GitOps toolkit for multi-tenant deployments.
- [Argo CD](https://argoproj.github.io/argo-cd/) - Declarative, GitOps continuous delivery tool for Kubernetes.

