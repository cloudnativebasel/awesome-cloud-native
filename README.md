# Awesome Cloud Native

A curated list of awesome resources around the Cloud Native landscape. ⭐

## Table of Contents

- [General Resources](#general-resources-%EF%B8%8F)
- [Containerization](#containerization-)
- [Orchestration](#orchestration-)
- [Microservices](#microservices-)
- [Service Mesh](#service-mesh-)
- [Immutable Infrastructure](#immutable-infrastructure-)
- [Cloud Providers](#cloud-providers-)
- [Edge Computing](#edge-computing-)
- [Serverless](#serverless-)
- [DevOps Practices](#devops-practices-)
- [CI/CD](#cicd-)
- [GitOps](#gitops-)
- [Observability and Monitoring](#observability-and-monitoring)
- [AI & Machine Learning](#ai-machine-learning)
- [WebAssembly](#webassembly)
- [Security and Governance](#security-and-governance)

## General Resources ☁️

- [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/) - The foundation behind Cloud Native ecosystem.
- [Cloud Native Landscape](https://landscape.cncf.io/) - An interactive landscape of cloud native technologies.
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) - A curated list of awesome Kubernetes resources.

## Containerization 📦

- [Docker](https://www.docker.com/) - Leading platform for containerization.
- [rkt](https://github.com/rkt/rkt) - Pod-native container engine, predates Docker in Kubernetes use.
- [containerd](https://containerd.io/) - A high-level container runtime.
- [cri-o](https://cri-o.io/) - Lightweight container runtime specifically for Kubernetes.
- [Crossplane](https://crossplane.io/) - Crossplane is an open-source Kubernetes add-on that transforms your cluster into a universal control plane to define and compose infrastructure and services directly from Kubernetes.

## Orchestration 🚢

- [Kubernetes](https://kubernetes.io/) - The de facto standard for container orchestration.
- [OpenShift](https://www.openshift.com/) - Kubernetes distribution by Red Hat with extra features.
- [Rancher](https://rancher.com/) - Complete container management platform built on Kubernetes.
- [Akri](https://github.com/deislabs/akri) - Akri is a project by Deis Labs that provides a framework for discovering and exposing heterogeneous leaf devices (like sensors) in a Kubernetes cluster.
- [HashiCorp's Nomad](https://www.nomadproject.io/) - Flexible and easy-to-use orchestrator that can deploy a mix of microservice, batch, and legacy applications.
- [KubeVirt](https://kubevirt.io/) - Lets you run virtual machines on Kubernetes alongside standard Kubernetes workloads.
- [Virtual Kubelet](https://virtual-kubelet.io/) - Enables nodes to be backed by other services like ACI, AWS Fargate, HashiCorp's Nomad etc.

## Microservices 🐛

- [Istio](https://istio.io/) - An open platform to connect, manage, and secure microservices.
- [Linkerd](https://linkerd.io/) - A service mesh for Kubernetes and other frameworks.
- [Envoy](https://www.envoyproxy.io/) - A high-performance, open-source edge and service proxy.
- [Dapr](https://dapr.io/) - Dapr is an open-source, portable, event-driven runtime that makes it easy for developers to build resilient, microservice, stateless and stateful applications.

## Service Mesh 🕸️

- [Istio](https://istio.io/) - Connects, manages, and secures microservices.
- [Linkerd](https://linkerd.io/) - Provides reliability and security to your services without requiring code changes.
- [Consul](https://www.consul.io/) - Provides a full-featured control plane with service discovery, configuration, and segmentation functionalities.
- [SMI (Service Mesh Interface)](https://smi-spec.io/) - Specification for service mesh APIs.
- [Maesh](https://github.com/traefik/mesh) - Simpler Service Mesh built on top of Traefik.

## Immutable Infrastructure ⛰️

- [Packer](https://www.packer.io/) - Builds automated machine images.
- [Terraform](https://www.terraform.io/) - Provides a common configuration to launch infrastructure.
- [Ansible](https://www.ansible.com/) - IT automation tool for just about everything that runs.

## Cloud Providers ⚓

- [Amazon Web Services (AWS)](https://aws.amazon.com/) - Offers reliable, scalable, and inexpensive cloud computing services.
- [Google Cloud Platform (GCP)](https://cloud.google.com/) - Suite of cloud computing services alongside a set of management tools.
- [Microsoft Azure](https://azure.microsoft.com/) - Build, deploy, and manage applications across global network of datacenters.

## Edge Computing 🏝️

- [KubeEdge](https://kubeedge.io/en/) - Provides network edge computing capabilities for Kubernetes.
- [OpenYurt](https://openyurt.io/en-us/) - OpenYurt by Alibaba turns Kubernetes into a platform for managing edge infrastructure.
- [K3s](https://k3s.io/) - Lightweight Kubernetes distribution perfect for edge computing.

## Serverless 🦋

- [AWS Lambda](https://aws.amazon.com/lambda/) - Lets you run your code without provisioning or managing servers.
- [Google Cloud Functions](https://cloud.google.com/functions) - Event-driven serverless compute platform.
- [Azure Functions](https://azure.microsoft.com/services/functions/) - Develop more efficiently with Functions, an event-driven serverless compute platform.
- [OpenFaaS](https://www.openfaas.com/) - Serverless Functions Made Simple for Docker and Kubernetes.
- [Knative](https://knative.dev/) - Extending Kubernetes to build, deploy, and manage modern serverless workloads.
- [Kubeless](https://kubeless.io/) - Kubernetes-native serverless framework.

## DevOps practices 🎋

- [Jenkins](https://www.jenkins.io/) - The leading open-source automation server for CI/CD.
- [Spinnaker](https://www.spinnaker.io/) - Multi-cloud continuous delivery platform.
- [GitLab](https://about.gitlab.com/) - Complete DevOps platform, delivered as a single application.

## CI/CD 🏗️

- [Jenkins](https://www.jenkins.io/) - Open-source automation tool with plugins built for continuous integration purposes.
- [CircleCI](https://circleci.com/) - Cloud-native continuous integration platform.
- [GitHub Actions](https://github.com/features/actions) - Workflow automation directly from GitHub repositories.
- [Travis CI](https://travis-ci.org/) - Hosted continuous integration service used to build and test software projects hosted on GitHub.
- [Keptn](https://keptn.sh/) - Keptn is a control plane for continuous delivery and automated operations for cloud-native applications.

## GitOps 🏛️

- [Flux](https://fluxcd.io/) - GitOps toolkit for multi-tenant deployments.
- [Argo CD](https://argoproj.github.io/argo-cd/) - Declarative, GitOps continuous delivery tool for Kubernetes.

## WebAssembly 🥡

- [Awesome Wasm](https://github.com/mbasso/awesome-wasm) - Curated list of awesome things regarding WebAssembly ecosystem.
- [Wasmtime](https://wasmtime.dev/) - Standalone runtime for WebAssembly.
- [AssemblyScript](https://www.assemblyscript.org/) - TypeScript to WebAssembly compiler.
- [WebAssembly (Wasm) Cloud](https://wasmcloud.com/) - wasmCloud is an open source project that leverages WebAssembly to allow developers to build portable business logic that can run securely anywhere.
- [Krustlet](https://github.com/deislabs/krustlet) - Krustlet is a Kubernetes Kubelet for running WebAssembly workloads. It's a project by Deis Labs.

## Networking 🧭

- [Cilium](https://cilium.io/) - Open source software for providing, securing, and observing network connectivity between container

## Storage 🪵

- [Rook](https://rook.io/) - Open-source, cloud-native storage orchestrator for Kubernetes.
- [Longhorn](https://longhorn.io/) - Project to provide a platform to build distributed block storage system for Kubernetes.
- [OpenEBS](https://openebs.io/) - OpenEBS is a Kubernetes native, open source Container Attached Storage (CAS) solution.

## AI & Machine Learning 🤖

- [Kubeflow](https://www.kubeflow.org/) - Machine Learning toolkit for Kubernetes.
- [Seldon Core](https://www.seldon.io/tech/products/core/) - Open source platform for deploying machine learning models on Kubernetes.
- [Feast (Feature Store)](https://feast.dev/) - Operationalizing Machine Learning at Scale.

## Security and Governance 🏯

- [Falco](https://falco.org/) - Open source cloud native runtime security project.
- [Open Policy Agent](https://www.openpolicyagent.org/) - General-purpose policy engine.
- [KubeLinter](https://github.com/stackrox/kube-linter) - Static analysis tool checking Kubernetes YAML files and Helm charts for misconfigurations.
- [kube-score](https://github.com/zegl/kube-score) - Kubernetes object analysis with recommendations for improved reliability and security.
- [SPIFFE](https://spiffe.io/) - Secure identity framework for production infrastructure.
- [Spire](https://spiffe.io/spire/) - Provides a unified way to issue, rotate, and revoke service identities.
- [Kyverno](https://kyverno.io/) - Kubernetes native policy management, used for validation, mutation, and generation of configurations.

## Observability and Monitoring 🛰️

- [Prometheus](https://prometheus.io/) - Open-source systems monitoring and alerting toolkit.
- [Grafana](https://grafana.com/) - Multi-platform open source analytics and interactive visualization platform.
- [Jaeger](https://www.jaegertracing.io/) - End-to-end distributed tracing for service mesh architectures.
- [OpenTelemetry](https://opentelemetry.io/) - Provides a single set of APIs, libraries, agents, and collector services to capture distributed traces and metrics.
- [Fluentd](https://www.fluentd.org/) - Open source data collector for unified logging layer.
- [Loki](https://grafana.com/oss/loki/) - Horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus.
- [Tempo](https://grafana.com/oss/tempo/) - Cost-effective, high-volume tracing system.
