# Developer Tools & Platform Engineering Frameworks

*Frameworks and tools for internal developer portals, infrastructure as code, secret management, orchestration, local environments, observability, and progressive delivery.*

## Contents

- [Internal Developer Portals (IDPs)](#internal-developer-portals-idps)
- [Infrastructure as Code (IaC) & GitOps](#infrastructure-as-code-iac--gitops)
- [Policy as Code & Governance](#policy-as-code--governance)
- [Secret Management & Credentials](#secret-management--credentials)
- [CI/CD Orchestration Engines](#cicd-orchestration-engines)
- [Service Mesh & Network Control](#service-mesh--network-control)
- [Cloud-Native Logging & Log Aggregation](#cloud-native-logging--log-aggregation)
- [APM & Distributed Tracing](#apm--distributed-tracing)
- [Local Development Environments](#local-development-environments)
- [Feature Flag & Progressive Delivery](#feature-flag--progressive-delivery)

---

## Internal Developer Portals (IDPs)

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Backstage | Open-source platform for building custom developer portals | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/backstage/backstage) • [Website](https://backstage.io) |
| Port | Developer portal framework that models software ecosystems | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/port-labs) • [Website](https://getport.io) |
| Roadie | Managed SaaS portal framework based on Spotify Backstage | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/roadie-hq) • [Website](https://roadie.io) |
| Mia-Platform | Internal Developer Portal framework to industrialize app delivery | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/mia-platform) • [Website](https://mia-platform.eu) |
| Cortex | Developer portal platform for cataloging and scoring microservices | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/cortex-apps) • [Website](https://www.cortex.io) |
| OpsLevel | Service catalog framework to build high-performance developer portals | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/OpsLevel) • [Website](https://www.opslevel.com) |
| Configure8 | Portal framework to centralize cataloging and developer workflows | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/configure8-io) • [Website](https://www.configure8.io) |
| Compass | Developer portal framework by Atlassian for distributed systems | <kbd>🏷️ Multi</kbd> | [Website](https://www.atlassian.com/software/compass) |
| Humanitec | Platform Orchestrator framework to build Internal Developer Platforms | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/humanitec) • [Website](https://humanitec.com) |
| Getport CLI | Command-line utility framework for configuring Port developer portals | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/port-labs/port-cli) • [Website](https://docs.getport.io) |
| Cycloid | DevOps framework for developer portals and infrastructure optimization | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/cycloidio) • [Website](https://www.cycloid.io) |
| KusionStack | Cloud-native developer application delivery and orchestration framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/KusionStack/kusion) • [Website](https://kusionstack.io) |
| backstage-plugins | Monorepo for community plugins expanding Spotify's Backstage portal | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/backstage/community-plugins) • [Website](https://backstage.io/plugins) |
| Chisel | Fast, secure TCP tunnel framework for developers | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/jpillora/chisel) • [Website](https://github.com/jpillora/chisel) |
| Wayfinder | Developer platform engineering portal for secure multi-cloud Kubernetes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/appvia/wayfinder) • [Website](https://www.appvia.io) |

## Infrastructure as Code (IaC) & GitOps

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Terraform | Tool for building, changing, and versioning infrastructure safely | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/hashicorp/terraform) • [Website](https://www.terraform.io) |
| Pulumi | Developer-first infrastructure as code using programming languages | <kbd>🏷️ Go/TS/Python</kbd> | [GitHub](https://github.com/pulumi/pulumi) • [Website](https://www.pulumi.com) |
| OpenTofu | Community-driven, open-source fork of Terraform | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/opentofu/opentofu) • [Website](https://opentofu.org) |
| Argo CD | Declarative GitOps continuous delivery tool for Kubernetes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/argoproj/argo-cd) • [Website](https://argoproj.github.io/cd/) |
| Flux CD | Open and extensible continuous delivery solution for Kubernetes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/fluxcd/flux2) • [Website](https://fluxcd.io) |
| Crossplane | Cloud-native control plane framework to manage infrastructure | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/crossplane/crossplane) • [Website](https://www.crossplane.io) |
| Ansible | Radically simple IT automation engine for config management | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/ansible/ansible) • [Website](https://www.ansible.com) |
| Chef | Configuration management framework for infrastructure automation | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/chef/chef) • [Website](https://www.chef.io) |
| Puppet | Declarative configuration management framework | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/puppetlabs/puppet) • [Website](https://www.puppet.com) |
| SaltStack | Software for event-driven IT automation and config management | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/saltstack/salt) • [Website](https://saltproject.io) |
| CloudFormation | Native AWS framework for provisioning resources | <kbd>🏷️ JSON/YAML</kbd> | [Website](https://aws.amazon.com/cloudformation/) |
| CDK8s | Cloud Development Kit for Kubernetes to define apps in code | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/cdk8s-team/cdk8s) • [Website](https://cdk8s.io) |
| CDKTF | Cloud Development Kit for Terraform using programming languages | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/hashicorp/terraform-cdk) • [Website](https://developer.hashicorp.com/terraform/cdktf) |
| AWS CDK | Cloud Development Kit to define cloud infrastructure using languages | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/aws/aws-cdk) • [Website](https://aws.amazon.com/cdk/) |
| Terragrunt | Thin wrapper for Terraform that provides extra tools | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gruntwork-io/terragrunt) • [Website](https://terragrunt.gruntwork.io) |

## Policy as Code & Governance

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| OPA | General-purpose policy engine that unifies policy enforcement | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/open-policy-agent/opa) • [Website](https://www.openpolicyagent.org) |
| Kyverno | Kubernetes-native policy management, generation, and validation | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/kyverno/kyverno) • [Website](https://kyverno.io) |
| Gatekeeper | Policy controller framework for Kubernetes using OPA | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/open-policy-agent/gatekeeper) • [Website](https://open-policy-agent.github.io/gatekeeper/website/) |
| Kube-score | Static code analysis tool for Kubernetes object definitions | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/zegl/kube-score) • [Website](https://github.com/zegl/kube-score) |
| Checkov | Static code analysis tool for infrastructure-as-code files | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/bridgecrewio/checkov) • [Website](https://www.checkov.io) |
| Kube-linter | Static analysis tool to check Kubernetes YAML files for best practices | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/stackrox/kube-linter) • [Website](https://github.com/stackrox/kube-linter) |
| Terrascan | Static code analyzer for infrastructure as code | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/tenable/terrascan) • [Website](https://runterrascan.io) |
| tfsec | Static analysis security scanner for your Terraform code | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/aquasecurity/tfsec) • [Website](https://aquasecurity.github.io/tfsec/) |
| DefectDojo | Open-source application vulnerability correlation and security orchestration | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/DefectDojo/django-DefectDojo) • [Website](https://www.defectdojo.org) |
| Sentinel | Embedded policy-as-code framework used across HashiCorp products | <kbd>🏷️ HCL</kbd> | [Website](https://developer.hashicorp.com/sentinel) |
| Polaris | Validation framework for Kubernetes deployment best practices | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/FairwindsOps/polaris) • [Website](https://polaris.docs.fairwinds.com) |
| Conftest | Test utility for configuration files using Open Policy Agent Rego | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/open-policy-agent/conftest) • [Website](https://www.conftest.dev) |
| Trivy Operator | Kubernetes-native security scanner operator | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/aquasecurity/trivy-operator) • [Website](https://aquasecurity.github.io/trivy-operator) |
| Falco | Cloud-native runtime security tool for system call monitoring | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/falcosecurity/falco) • [Website](https://falco.org) |
| Cloud Custodian | Rules engine for cloud security, cost, and compliance governance | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/cloud-custodian/cloud-custodian) • [Website](https://cloudcustodian.io) |

## Secret Management & Credentials

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Vault | Tool for securely accessing secrets, API keys, and passwords | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/hashicorp/vault) • [Website](https://www.vaultproject.io) |
| SOPS | Secrets Operations framework for encrypting config files | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/getsops/sops) • [Website](https://github.com/getsops/sops) |
| External Secrets | Kubernetes operator integrating secret managers into k8s | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/external-secrets/external-secrets) • [Website](https://external-secrets.io) |
| Sealed Secrets | One-way encrypted secrets framework for Kubernetes GitOps | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/bitnami-labs/sealed-secrets) • [Website](https://github.com/bitnami-labs/sealed-secrets) |
| Infisical | Developer-first secret management platform for teams | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/Infisical/infisical) • [Website](https://infisical.com) |
| Doppler | Developer-focused central secret management and sync platform | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/DopplerHQ) • [Website](https://doppler.com) |
| Bank-Vaults | Vault helper and operator wrapper framework for Kubernetes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/bank-vaults/bank-vaults) • [Website](https://bank-vaults.dev) |
| CyberArk Conjur | Enterprise secrets manager and secure credentials broker | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/cyberark/conjur) • [Website](https://www.conjur.org) |
| Akeyless | SaaS-based secret management and password protection platform | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/akeyless-community) • [Website](https://www.akeyless.io) |
| Knox | Apache-developed service gateway and credential provider | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/apache/knox) • [Website](https://knox.apache.org) |
| Keep | Alerts management platform that securely manages environment credentials | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/keephq/keep) • [Website](https://www.keephq.dev) |
| Teller | Cloud-native secrets management tool for developers | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/tellerops/teller) • [Website](https://teller.sh) |
| Bitwarden Secrets | Developer platform for securely storing machine credentials and tokens | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/bitwarden/sdk) • [Website](https://bitwarden.com/products/secrets-manager/) |
| Chamber | Utility tool for managing secrets stored in AWS Parameter Store | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/segmentio/chamber) • [Website](https://github.com/segmentio/chamber) |
| AWS Secrets SDK | AWS SDK wrapper for retrieving encrypted configuration data | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/aws/aws-secretsmanager-caching-java) • [Website](https://aws.amazon.com/secrets-manager/) |

## CI/CD Orchestration Engines

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Jenkins | Leading open-source automation server for building and deploying | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/jenkinsci/jenkins) • [Website](https://www.jenkins.io) |
| GitLab Runner | Open-source project used to run CI jobs and send results to GitLab | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gitlabhq/gitlab-runner) • [Website](https://docs.gitlab.com/runner/) |
| Tekton | Powerful and flexible Kubernetes-native CI/CD framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/tektoncd/pipeline) • [Website](https://tekton.dev) |
| Drone | Pragmatic, container-native continuous delivery platform | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/harness/drone) • [Website](https://drone.io) |
| Concourse | CI/CD pipeline engine featuring pipeline-as-code and containers | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/concourse/concourse) • [Website](https://concourse-ci.org) |
| Spinnaker | Multi-cloud continuous delivery platform for enterprise deployments | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/spinnaker/spinnaker) • [Website](https://spinnaker.io) |
| GitHub Runner | The runner execution engine powering GitHub Actions workflows | <kbd>🏷️ C#</kbd> | [GitHub](https://github.com/actions/runner) • [Website](https://github.com/actions/runner) |
| CircleCI Runner | Runner framework allowing self-hosted jobs on CircleCI pipelines | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/CircleCI-Public/runner-installation) • [Website](https://circleci.com) |
| Woodpecker CI | Community-driven, docker-native CI engine fork of Drone | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/woodpecker-ci/woodpecker) • [Website](https://woodpecker-ci.org) |
| GoCD | Continuous delivery tool with advanced pipeline dependency visualization | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/gocd/gocd) • [Website](https://www.gocd.org) |
| Argo Workflows | Container-native workflow engine for orchestrating jobs on Kubernetes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/argoproj/argo-workflows) • [Website](https://argoproj.github.io/workflows/) |
| Zuul | Enterprise CI/CD engine designed for multi-repository gated testing | <kbd>🏷️ Python</kbd> | [GitHub](https://opendev.org/zuul/zuul) • [Website](https://zuul-ci.org) |
| Earthly | Supercharged build automation tool executing builds in containers | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/earthly/earthly) • [Website](https://earthly.dev) |
| Buildkite Agent | Lightweight build runner agent for Buildkite hybrid CI pipelines | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/buildkite/agent) • [Website](https://buildkite.com) |
| Dagger | Portable dev engine executing CI/CD pipelines in containers | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/dagger/dagger) • [Website](https://dagger.io) |

## Service Mesh & Network Control

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Istio | Service mesh framework offering load balancing and routing | <kbd>🏷️ Go/C++</kbd> | [GitHub](https://github.com/istio/istio) • [Website](https://istio.io) |
| Linkerd | Ultralight, security-first service mesh for Kubernetes | <kbd>🏷️ Go/Rust</kbd> | [GitHub](https://github.com/linkerd/linkerd2) • [Website](https://linkerd.io) |
| Consul Connect | Service mesh functionality built on HashiCorp Consul | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/hashicorp/consul) • [Website](https://www.consul.io) |
| Kuma | Multi-zone service mesh control plane built on Envoy proxy | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/kumahq/kuma) • [Website](https://kuma.io) |
| Cilium | eBPF-based networking, security, and service mesh platform | <kbd>🏷️ Go/C</kbd> | [GitHub](https://github.com/cilium/cilium) • [Website](https://cilium.io) |
| Traefik Mesh | Lightweight service mesh built on top of Traefik proxy | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/traefik/mesh) • [Website](https://traefik.io/traefik-mesh/) |
| OSM | Lightweight, extensible Open Service Mesh based on Envoy proxy | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/openservicemesh/osm) • [Website](https://openservicemesh.io) |
| NGINX Mesh | Lightweight service mesh for NGINX-powered environments | <kbd>🏷️ Go</kbd> | [Website](https://www.nginx.com/products/nginx-service-mesh/) |
| Kong Mesh | Enterprise service mesh built on top of Kuma | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/Kong/kumactl) • [Website](https://konghq.com/products/kong-mesh) |
| App Mesh | Managed service mesh providing application-level networking | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/aws/aws-app-mesh-controller-for-k8s) • [Website](https://aws.amazon.com/app-mesh/) |
| Calico | Container networking and security policy engine | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/projectcalico/calico) • [Website](https://www.tigera.io/project-calico/) |
| Ambient Mesh | Sidecarless deployment architecture extension for Istio mesh | <kbd>🏷️ Rust/Go</kbd> | [GitHub](https://github.com/istio/istio) • [Website](https://istio.io/latest/docs/ops/ambient/) |
| Envoy | High-performance edge and service proxy designed for cloud-native apps | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/envoyproxy/envoy) • [Website](https://www.envoyproxy.io) |
| Traefik | HTTP reverse proxy and load balancer designed for microservices | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/traefik/traefik) • [Website](https://traefik.io) |
| BungeeCord | Teleport and routing proxy suite for Java applications | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/SpigotMC/BungeeCord) • [Website](https://www.spigotmc.org) |

## Cloud-Native Logging & Log Aggregation

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Fluentd | Data collector framework for unifying logging infrastructures | <kbd>🏷️ Ruby/C</kbd> | [GitHub](https://github.com/fluent/fluentd) • [Website](https://www.fluentd.org) |
| Fluent Bit | Fast, lightweight log processor and forwarder for cloud environments | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/fluent/fluent-bit) • [Website](https://fluentbit.io) |
| Logstash | Server-side data processing pipeline ingesting from multiple sources | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/elastic/logstash) • [Website](https://www.elastic.co/logstash) |
| Loki | Horizontally-scalable, highly-available, multi-tenant log aggregation | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/grafana/loki) • [Website](https://grafana.com/oss/loki/) |
| Vector | High-performance tool for building observability pipelines | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/vectordotdev/vector) • [Website](https://vector.dev) |
| Graylog | Centralized log management and analytics system | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/Graylog2/graylog2-server) • [Website](https://graylog.org) |
| Logging Operator | Cloud-native logging operator framework developed by Banzai | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/kube-logging/logging-operator) • [Website](https://kube-logging.github.io/logging-operator/) |
| Promtail | Agent shipping local logs to Grafana Loki instance | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/grafana/loki/tree/main/clients/cmd/promtail) • [Website](https://grafana.com/docs/loki/latest/send-data/promtail/) |
| Otel Collector | Vendor-agnostic receiver, processor, and exporter proxy for metrics | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/open-telemetry/opentelemetry-collector) • [Website](https://opentelemetry.io/docs/collector/) |
| Rsyslog | Rocket-fast system for log processing and packet forwarding | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/rsyslog/rsyslog) • [Website](https://www.rsyslog.com) |
| Filebeat | Lightweight log shipper for sending files to Elasticsearch | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/elastic/beats/tree/main/filebeat) • [Website](https://www.elastic.co/beats/filebeat) |
| Logspout | Log router for Docker container stdout/stderr streams | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gliderlabs/logspout) • [Website](https://github.com/gliderlabs/logspout) |
| Journalbeat | Daemon shipper for systemd journald log collection | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/elastic/beats/tree/main/journalbeat) • [Website](https://www.elastic.co/beats/journalbeat) |
| Winlogbeat | Windows event logs shipper for remote collection | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/elastic/beats/tree/main/winlogbeat) • [Website](https://www.elastic.co/beats/winlogbeat) |
| Apache Flume | Distributed service for collecting, aggregating, and moving log data | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/apache/flume) • [Website](https://flume.apache.org) |

## APM & Distributed Tracing

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Jaeger | Open-source, end-to-end distributed tracing monitor | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/jaegertracing/jaeger) • [Website](https://www.jaegertracing.io) |
| OpenTelemetry SDK | Telemetry SDK for generating logs, metrics, and tracing telemetry | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/open-telemetry) • [Website](https://opentelemetry.io) |
| Prometheus | Cloud-native monitoring system and time-series database | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/prometheus/prometheus) • [Website](https://prometheus.io) |
| OpenMetrics | Specification for exporting metrics data in cloud environments | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/OpenObservability/OpenMetrics) • [Website](https://openmetrics.io) |
| SkyWalking | APM system designed for microservices and cloud-native systems | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/apache/skywalking) • [Website](https://skywalking.apache.org) |
| Zipkin | Distributed tracing system helping gather timing data for debug | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/openzipkin/zipkin) • [Website](https://zipkin.io) |
| SigNoz | Developer-friendly APM and observability platform | <kbd>🏷️ TypeScript/Go</kbd> | [GitHub](https://github.com/SigNoz/signoz) • [Website](https://signoz.io) |
| Pinpoint | Large-scale APM tool for Java / PHP microservice systems | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/pinpoint-apm/pinpoint) • [Website](https://pinpoint-apm.github.io/pinpoint/) |
| Pyroscope | Continuous profiling framework designed for optimization and debug | <kbd>🏷️ Go/Rust</kbd> | [GitHub](https://github.com/grafana/pyroscope) • [Website](https://pyroscope.io) |
| Pixie | Instantly auto-instrumented eBPF-powered observability for Kubernetes | <kbd>🏷️ C++/Go</kbd> | [GitHub](https://github.com/pixie-io/pixie) • [Website](https://pixielabs.ai) |
| Netdata | Real-time monitoring agent for systems and application performance | <kbd>🏷️ C/Python</kbd> | [GitHub](https://github.com/netdata/netdata) • [Website](https://www.netdata.cloud) |
| Grafana Tempo | Cost-effective, high-volume distributed tracing backend | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/grafana/tempo) • [Website](https://grafana.com/oss/tempo/) |
| Kamon | Monitoring and APM library for JVM applications (Scala/Java) | <kbd>🏷️ Scala</kbd> | [GitHub](https://github.com/kamon-io/Kamon) • [Website](https://kamon.io) |
| Elastic APM | Application performance monitoring agents developed by Elastic | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/elastic/apm-server) • [Website](https://www.elastic.co/observability/apm) |
| Dynatrace OneAgent | Proprietary SDK wrapper for tracing complex microservice transactions | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/Dynatrace/OneAgent-SDK) • [Website](https://www.dynatrace.com) |

## Local Development Environments

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| DevSpace | Client-only CLI developer tool for building on Kubernetes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/loft-sh/devspace) • [Website](https://devspace.sh) |
| Skaffold | Command-line tool facilitating continuous development for Kubernetes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/GoogleContainerTools/skaffold) • [Website](https://skaffold.dev) |
| Tilt | High-performance tool helping developers iterate on Kubernetes clusters | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/tilt-dev/tilt) • [Website](https://tilt.dev) |
| Telepresence | Local development environment proxy for Kubernetes applications | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/telepresence/telepresence) • [Website](https://www.telepresence.io) |
| Garden | Universal framework for building, testing, and deploying pipelines | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/garden-io/garden) • [Website](https://garden.io) |
| LocalStack | Fully functional local AWS cloud stack for testing and dev | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/localstack/localstack) • [Website](https://localstack.cloud) |
| Lando | Development utility wrapper around Docker Compose | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/lando/lando) • [Website](https://lando.dev) |
| DDEV | PHP/Node local development tool built on top of Docker | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/ddev/ddev) • [Website](https://ddev.com) |
| Docksal | Container-based local development environment environment switcher | <kbd>🏷️ Bash/PHP</kbd> | [GitHub](https://github.com/docksal/docksal) • [Website](https://docksal.io) |
| Podman | Daemonless tool for running, storing and finding container images | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/containers/podman) • [Website](https://podman.io) |
| Minikube | Runs a local, single-node Kubernetes cluster on virtual machines | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/kubernetes/minikube) • [Website](https://minikube.sigs.k8s.io) |
| Kind | Utility framework for running local Kubernetes clusters using Docker | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/kubernetes-sigs/kind) • [Website](https://kind.sigs.k8s.io) |
| K3d | Lightweight wrapper to run k3s (Kubernetes) in Docker | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/k3d-io/k3d) • [Website](https://k3d.io) |
| Multipass | Ubuntu VM manager framework for rapid sandbox environments | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/canonical/multipass) • [Website](https://multipass.run) |
| Finch | Open-source CLI client for container management and sandboxing | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/runfinch/finch) • [Website](https://runfinch.com) |

## Feature Flag & Progressive Delivery

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Unleash | Enterprise-grade open-source feature toggle service API | <kbd>🏷️ TypeScript/Go</kbd> | [GitHub](https://github.com/Unleash/unleash) • [Website](https://www.getunleash.io) |
| Flagsmith | Feature flag and remote config framework for frontend/backend | <kbd>🏷️ Python/JS</kbd> | [GitHub](https://github.com/Flagsmith/flagsmith) • [Website](https://www.flagsmith.com) |
| Keptn | Cloud-native deployment lifecycle and progressive delivery controller | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/keptn/keptn) • [Website](https://keptn.sh) |
| Flagger | Progressive delivery operator framework for traffic routing control | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/fluxcd/flagger) • [Website](https://flagger.app) |
| Argo Rollouts | Kubernetes controller providing advanced progressive delivery features | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/argoproj/argo-rollouts) • [Website](https://argoproj.github.io/argo-rollouts/) |
| OpenFeature | Open standard API specification for unified feature flag engines | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/open-feature) • [Website](https://openfeature.dev) |
| GrowthBook | Feature flagging platform with a built-in A/B testing framework | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/growthbook/growthbook) • [Website](https://www.growthbook.io) |
| FeatureGates | Lightweight SDK for user segmentation and feature flag validation | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/statsig-io/js-client-monorepo) • [Website](https://statsig.com) |
| DevCycle | Developer-focused feature flag tool with CLI and package sync | <kbd>🏷️ Go/TS</kbd> | [GitHub](https://github.com/DevCycleHQ) • [Website](https://devcycle.com) |
| Flipper | Elegant feature flipping library for Ruby applications | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/flippercloud/flipper) • [Website](https://flippercloud.io) |
| FF4J | Feature Flags for Java implementation framework | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/ff4j/ff4j) • [Website](https://ff4j.org) |
| Togglz | Feature flags pattern implementation for Java/Jakarta EE | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/togglz/togglz) • [Website](https://www.togglz.org) |
| Funnel | Traffic funneling and feature gating API framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/open-telemetry) • [Website](https://github.com/open-telemetry) |
| LaunchDarkly SDK | Multi-language clients for LaunchDarkly flag management system | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/launchdarkly) • [Website](https://launchdarkly.com) |
| Split SDK | Client libraries for split-testing and progressive feature rollouts | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/splitio) • [Website](https://www.split.io) |
