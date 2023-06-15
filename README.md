![awesome-cloud-native-header](https://github.com/cloudnativebasel/static/blob/main/images/awesome-cloud-native-header.png)

# Awesome Cloud Native

A curated list of awesome resources around the Cloud Native landscape. ⭐

## Table of Contents

- [General Resources](#general-resources-%EF%B8%8F)
- [Containerization](#containerization-)
- [Container Runtime Interface](#container-runtime-interface-)
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
- [Observability and Monitoring](#observability-and-monitoring-)
- [AI & Machine Learning](#ai--machine-learning-)
- [WebAssembly](#webassembly-)
- [Security and Governance](#security-and-governance-)
- [Cloud Native Web Frameworks and Languages](#cloud-native-web-frameworks-and-languages)
  - [Web Frameworks](#web-frameworks-)
  - [Languages](#languages-)


## General Resources ☁️

- [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/) - The foundation behind Cloud Native ecosystem.
- [Cloud Native Landscape](https://landscape.cncf.io/) - An interactive landscape of cloud native technologies.
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) - A curated list of awesome Kubernetes resources.

## Containerization 📦

- [Docker](https://www.docker.com/) - Leading platform for containerization.
- [rkt](https://github.com/rkt/rkt) - Pod-native container engine, predates Docker in Kubernetes use.
- [containerd](https://containerd.io/) - A high-level container runtime.
- [cri-o](https://cri-o.io/) - Lightweight container runtime specifically for Kubernetes.
- [Podman](https://podman.io/): Podman is a daemonless container engine for developing, managing, and running OCI Containers on your Linux System.
- [Buildah](https://buildah.io/): Buildah is a tool that facilitates building Open Container Initiative (OCI) container images.
- [Crossplane](https://crossplane.io/) - Crossplane is an open-source Kubernetes add-on that transforms your cluster into a universal control plane to define and compose infrastructure and services directly from Kubernetes.

## Container Runtime Interface 🧳

- [gVisor](https://gvisor.dev/): gVisor is a user-space kernel, written in Go, that implements a substantial portion of the Linux system surface. It provides an isolation boundary between the application and the host kernel and integrates with Docker and Kubernetes, providing sandboxed containers.
- [Kata Containers](https://katacontainers.io/): Kata Containers project offers lightweight VMs that perform like containers, but provide stronger workload isolation using hardware virtualization technology as a second layer of defense.
- [Firecracker](https://firecracker-microvm.github.io/): Firecracker is an open-source virtualization technology that is purpose-built for creating and managing secure, multi-tenant container and function-based services. It was developed by Amazon Web Services (AWS) to improve the efficiency and resource sharing of their Lambda and Fargate services. Firecracker provides lightweight virtual machines called microVMs.

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
- [Spacelift](https://spacelift.io/) - Spacelift is a Continuous Delivery platform designed specifically to handle Infrastructure as Code (IaC).

## Cloud Providers ⚓

- [Amazon Web Services (AWS)](https://aws.amazon.com/) - Biggest cloud provider; offers reliable, scalable cloud computing services.
- [Google Cloud Platform (GCP)](https://cloud.google.com/) - Google's cloud provider offering; similar in quality and offering as AWS.
- [Microsoft Azure](https://azure.microsoft.com/) - Microsoft's cloud provider offering; focused on Windows and Microsoft product integration.
- [DigitalOcean (DO)](https://www.digitalocean.com/): DigitalOcean is a cloud infrastructure provider focused on simplifying web infrastructure for software developers.
- [Heroku](https://www.heroku.com/): Heroku is a cloud platform as a service supporting several programming languages.
- [Vercel](https://vercel.com/): Vercel is the platform for frontend developers, providing the speed and reliability innovators need to create at the moment of inspiration.
- [Netlify](https://www.netlify.com/): A powerful serverless platform with an intuitive git-based workflow. Automated deployments, shareable previews, and much more.
- [Flow Swiss](https://flow.swiss): 
- [Fly](https://fly.io/): Purpose-Built Cloud. We run physical servers in cities close to your users. As close to the metal as you can get without paying shipping.

## Edge Computing 🏝️

- [KubeEdge](https://kubeedge.io/en/) - Provides network edge computing capabilities for Kubernetes.
- [OpenYurt](https://openyurt.io/en-us/) - OpenYurt by Alibaba turns Kubernetes into a platform for managing edge infrastructure.
- [K3s](https://k3s.io/) - Lightweight Kubernetes distribution perfect for edge computing.

## Serverless 🦋

- [AWS Lambda](https://aws.amazon.com/lambda/) - Lets you run your code without provisioning or managing servers.
- [Google Cloud Functions](https://cloud.google.com/functions) - Event-driven serverless compute platform.
- [Azure Functions](https://azure.microsoft.com/services/functions/) - Develop more efficiently with Functions, an event-driven serverless compute platform.
- [OpenFaaS](https://www.openfaas.com/) - Serverless Functions Made Simple for Docker and Kubernetes.
- [Serverless Framework](https://www.serverless.com/): All-in-one development solution for auto-scaling apps on AWS Lambda.
- [Knative](https://knative.dev/) - Extending Kubernetes to build, deploy, and manage modern serverless workloads.
- [AWS Amplify](https://aws.amazon.com/amplify/): Amplify is a development platform for building secure, scalable mobile and web applications.
- [Zappa](https://github.com/zappa/Zappa): Zappa is a serverless framework for Python applications. It allows you to build and deploy serverless Python applications on AWS with a minimal configuration and overhead.
- [Chalice](https://github.com/aws/chalice): Also for Python developers, Chalice is an AWS-backed serverless framework.

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

## Cloud-Native Web Frameworks and Languages

### Web Frameworks 🪆

- [Flask](https://flask.palletsprojects.com/en/2.1.x/) - Micro web framework written in Python.
- [Spring Boot](https://spring.io/projects/spring-boot) - Java-based framework used to create stand-alone, production-grade Spring-based Applications.
- [Phoenix](https://www.phoenixframework.org/) - A productive web framework that does not compromise speed or maintainability.
- [NestJS](https://nestjs.com/) - A progressive Node.js framework for building efficient, reliable and scalable server-side applications.
- [Micronaut](https://micronaut.io/) - A modern, JVM-based, full-stack framework for building modular, easily testable microservice applications.
- [Quarkus](https://quarkus.io/) - A Kubernetes-native Java stack tailored for GraalVM and OpenJDK HotSpot, crafted from the best of breed Java libraries and standards.
- [FastAPI](https://fastapi.tiangolo.com/) - A modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
- [Bun](https://bun.sh/) - A fast, all-in-one JavaScript runtime with a bundler, package manager, and a beautiful logger built-in.
- [Tauri](https://tauri.app/): Build smaller, faster, and more secure desktop applications with a web frontend.
- [Tokio](https://tokio.rs/) - A Rust runtime for writing reliable network applications without compromising speed.
- [Phoenix](https://www.phoenixframework.org/) - A productive web framework that does not compromise speed or maintainability.

### Languages 📟

- [Go](https://golang.org/) - Go is an open source programming language that makes it easy to build simple, reliable, and efficient software.
- [Deno](https://deno.land/) - A secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust
- [Rust](https://www.rust-lang.org/) - A language empowering everyone to build reliable and efficient software. It is designed to provide memory safety while maintaining high performance.
- [Python](https://www.python.org/) - Python is a programming language that lets you work quickly and integrate systems more effectively.
- [Elixir](https://elixir-lang.org/) - A dynamic, functional language designed for building scalable and maintainable applications. Elixir leverages the Erlang VM, known for running low-latency, distributed, and fault-tolerant systems.
