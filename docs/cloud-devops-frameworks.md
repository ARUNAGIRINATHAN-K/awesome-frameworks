# Cloud & DevOps Frameworks

*Comprehensive list of cloud and DevOps frameworks, tools, and platforms grouped by category.*

## Contents

- [Infrastructure as Code (IaC) Frameworks](#infrastructure-as-code-iac-frameworks)
- [CI/CD Frameworks](#cicd-frameworks)
- [Containerization Frameworks](#containerization-frameworks)
- [Container Orchestration Frameworks](#container-orchestration-frameworks)
- [Cloud Provider Frameworks & SDKs](#cloud-provider-frameworks--sdks)
- [Serverless Frameworks](#serverless-frameworks)
- [Monitoring & Observability Frameworks](#monitoring--observability-frameworks)
- [Service Mesh Frameworks](#service-mesh-frameworks)
- [Security & Compliance Frameworks](#security--compliance-frameworks)
- [GitOps Frameworks](#gitops-frameworks)
- [Cloud Networking Frameworks](#cloud-networking-frameworks)
- [Cloud Cost Management Frameworks](#cloud-cost-management-frameworks)
- [DevOps Testing Frameworks](#devops-testing-frameworks)
- [Artifact & Registry Frameworks](#artifact--registry-frameworks)

---

## Infrastructure as Code (IaC) Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Terraform | Multi-cloud infrastructure provisioning | <kbd>🏷️ HCL</kbd> | [GitHub](https://github.com/hashicorp/terraform) • [Website](https://www.terraform.io) |
| Pulumi | Cloud infrastructure with real code | <kbd>🏷️ Multi-language</kbd> | [GitHub](https://github.com/pulumi/pulumi) • [Website](https://www.pulumi.com) |
| AWS CDK | AWS infrastructure as code | <kbd>🏷️ TypeScript/Python</kbd> | [GitHub](https://github.com/aws/aws-cdk) • [Website](https://aws.amazon.com/cdk/) |
| Azure Bicep | Azure native IaC framework | <kbd>🏷️ Bicep</kbd> | [GitHub](https://github.com/Azure/bicep) • [Website](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/) |
| Google Cloud Deployment Manager | GCP infrastructure provisioning | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/GoogleCloudPlatform/deploymentmanager-samples) • [Website](https://cloud.google.com/deployment-manager) |
| OpenTofu | Open-source Terraform fork | <kbd>🏷️ HCL</kbd> | [GitHub](https://github.com/opentofu/opentofu) • [Website](https://opentofu.org) |
| Crossplane | Kubernetes-based IaC framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/crossplane/crossplane) • [Website](https://www.crossplane.io) |
| Ansible | Agentless configuration management | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/ansible/ansible) • [Website](https://www.ansible.com) |
| Chef | Infrastructure automation framework | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/chef/chef) • [Website](https://www.chef.io) |
| Puppet | Configuration management framework | <kbd>🏷️ DSL</kbd> | [GitHub](https://github.com/puppetlabs/puppet) • [Website](https://www.puppet.com) |
| SaltStack | Event-driven infrastructure automation | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/saltstack/salt) • [Website](https://saltproject.io) |
| CFEngine | Lightweight config management | <kbd>🏷️ DSL</kbd> | [GitHub](https://github.com/cfengine/core) • [Website](https://cfengine.com) |
| Vagrant | Development environment provisioning | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/hashicorp/vagrant) • [Website](https://www.vagrantup.com) |
| Packer | Machine image builder framework | <kbd>🏷️ HCL</kbd> | [GitHub](https://github.com/hashicorp/packer) • [Website](https://www.packer.io) |

## CI/CD Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Jenkins | Open-source CI/CD automation | <kbd>🏷️ Groovy</kbd> | [GitHub](https://github.com/jenkinsci/jenkins) • [Website](https://www.jenkins.io) |
| GitHub Actions | GitHub native CI/CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/features/actions) • [Website](https://docs.github.com/en/actions) |
| GitLab CI/CD | GitLab native pipeline framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/gitlabhq/gitlabhq) • [Website](https://docs.gitlab.com/ee/ci/) |
| CircleCI | Cloud-based CI/CD platform | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/circleci) • [Website](https://circleci.com) |
| Travis CI | GitHub-integrated CI framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/travis-ci/travis-ci) • [Website](https://www.travis-ci.com) |
| Bamboo | Atlassian CI/CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/atlassian/bamboo-specs) • [Website](https://www.atlassian.com/software/bamboo) |
| TeamCity | JetBrains CI/CD framework | <kbd>🏷️ Kotlin/XML</kbd> | [GitHub](https://github.com/JetBrains/teamcity-documentation) • [Website](https://www.jetbrains.com/teamcity/) |
| Azure Pipelines | Microsoft CI/CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/microsoft/azure-pipelines-agent) • [Website](https://azure.microsoft.com/en-us/products/devops/pipelines) |
| AWS CodePipeline | AWS native CI/CD framework | <kbd>🏷️ JSON</kbd> | [GitHub](https://github.com/aws/aws-codepipeline-user-guide) • [Website](https://aws.amazon.com/codepipeline/) |
| Google Cloud Build | GCP CI/CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/GoogleCloudPlatform/cloud-builders) • [Website](https://cloud.google.com/build) |
| Bitbucket Pipelines | Atlassian cloud CI/CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/atlassian/pipelines-examples) • [Website](https://bitbucket.org/product/features/pipelines) |
| DroneCI | Container-native CI framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/harness/drone) • [Website](https://www.drone.io) |
| Tekton | Kubernetes-native CI/CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/tektoncd/pipeline) • [Website](https://tekton.dev) |
| ArgoCD | GitOps CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/argoproj/argo-cd) • [Website](https://argo-cd.readthedocs.io) |
| Flux | GitOps toolkit for Kubernetes | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/fluxcd/flux2) • [Website](https://fluxcd.io) |
| Spinnaker | Multi-cloud CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/spinnaker/spinnaker) • [Website](https://spinnaker.io) |
| Harness | AI-powered CI/CD platform | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/harness/harness) • [Website](https://www.harness.io) |
| GoCD | Open-source CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/gocd/gocd) • [Website](https://www.gocd.org) |

## Containerization Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Docker | Container creation & management | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/docker/docker-ce) • [Website](https://www.docker.com) |
| Podman | Daemonless container framework | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/containers/podman) • [Website](https://podman.io) |
| Buildah | Container image building tool | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/containers/buildah) • [Website](https://buildah.io) |
| Skopeo | Container image management | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/containers/skopeo) • [Website](https://github.com/containers/skopeo) |
| LXC | Linux container framework | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/lxc/lxc) • [Website](https://linuxcontainers.org) |
| containerd | Container runtime framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/containerd/containerd) • [Website](https://containerd.io) |
| CRI-O | Kubernetes container runtime | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/cri-o/cri-o) • [Website](https://cri-o.io) |
| Kaniko | Container build in Kubernetes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/GoogleContainerTools/kaniko) • [Website](https://github.com/GoogleContainerTools/kaniko) |
| Buildkit | Next-gen Docker build engine | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/moby/buildkit) • [Website](https://docs.docker.com/build/buildkit/) |
| Distroless | Minimal container base images | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/GoogleContainerTools/distroless) • [Website](https://github.com/GoogleContainerTools/distroless) |

## Container Orchestration Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Kubernetes | Container orchestration platform | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/kubernetes/kubernetes) • [Website](https://kubernetes.io) |
| Docker Swarm | Docker native orchestration | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/docker/swarmkit) • [Website](https://docs.docker.com/engine/swarm/) |
| Apache Mesos | Distributed systems kernel | <kbd>🏷️ Scala</kbd> | [GitHub](https://github.com/apache/mesos) • [Website](https://mesos.apache.org) |
| Nomad | HashiCorp workload orchestrator | <kbd>🏷️ HCL</kbd> | [GitHub](https://github.com/hashicorp/nomad) • [Website](https://www.nomadproject.io) |
| OpenShift | Red Hat Kubernetes platform | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/openshift/origin) • [Website](https://www.redhat.com/en/technologies/cloud-computing/openshift) |
| Rancher | Kubernetes management platform | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/rancher/rancher) • [Website](https://www.rancher.com) |
| K3s | Lightweight Kubernetes framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/k3s-io/k3s) • [Website](https://k3s.io) |
| MicroK8s | Canonical lightweight Kubernetes | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/canonical/microk8s) • [Website](https://microk8s.io) |
| Kind | Kubernetes in Docker | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/kubernetes-sigs/kind) • [Website](https://kind.sigs.k8s.io) |
| Minikube | Local Kubernetes framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/kubernetes/minikube) • [Website](https://minikube.sigs.k8s.io) |
| Helm | Kubernetes package manager | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/helm/helm) • [Website](https://helm.sh) |
| Kustomize | Kubernetes config management | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/kubernetes-sigs/kustomize) • [Website](https://kustomize.io) |
| Operator Framework | Kubernetes operator framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/operator-framework/operator-sdk) • [Website](https://operatorframework.io) |
| KEDA | Kubernetes event-driven autoscaling | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/kedacore/keda) • [Website](https://keda.sh) |

## Cloud Provider Frameworks & SDKs

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| AWS SDK | Amazon Web Services SDK | <kbd>🏷️ Multi-language</kbd> | [GitHub](https://github.com/aws/aws-sdk) • [Website](https://aws.amazon.com/developer/tools/) |
| Azure SDK | Microsoft Azure SDK | <kbd>🏷️ Multi-language</kbd> | [GitHub](https://github.com/Azure/azure-sdk) • [Website](https://azure.microsoft.com/en-us/downloads/) |
| Google Cloud SDK | Google Cloud Platform SDK | <kbd>🏷️ Multi-language</kbd> | [GitHub](https://github.com/googleapis/google-cloud-python) • [Website](https://cloud.google.com/sdk) |
| AWS SAM | Serverless application model | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/aws/serverless-application-model) • [Website](https://aws.amazon.com/serverless/sam/) |
| AWS Amplify | Full-stack cloud framework | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/aws-amplify/amplify-js) • [Website](https://aws.amazon.com/amplify/) |
| Firebase | Google mobile/web backend | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/firebase/firebase-js-sdk) • [Website](https://firebase.google.com) |
| Supabase | Open-source Firebase alternative | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/supabase/supabase) • [Website](https://supabase.com) |
| Cloudflare Workers | Edge computing framework | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/cloudflare/workers-sdk) • [Website](https://workers.cloudflare.com) |
| Vercel | Frontend cloud platform | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/vercel/vercel) • [Website](https://vercel.com) |
| Netlify | JAMstack deployment platform | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/netlify/netlify-cms) • [Website](https://www.netlify.com) |
| Fly.io | App deployment framework | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/superfly/flyctl) • [Website](https://fly.io) |
| Railway | Cloud deployment platform | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/railwayapp/cli) • [Website](https://railway.app) |
| Render | Cloud application platform | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/render-oss/render-cli) • [Website](https://render.com) |
| DigitalOcean App Platform | Simplified cloud deployment | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/digitalocean/doctl) • [Website](https://www.digitalocean.com/products/app-platform) |

## Serverless Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Serverless Framework | Multi-cloud serverless deployment | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/serverless/serverless) • [Website](https://www.serverless.com) |
| AWS Lambda | AWS serverless functions | <kbd>🏷️ Multi-language</kbd> | [GitHub](https://github.com/aws/aws-lambda-base-images) • [Website](https://aws.amazon.com/lambda/) |
| Azure Functions | Microsoft serverless framework | <kbd>🏷️ Multi-language</kbd> | [GitHub](https://github.com/Azure/azure-functions-host) • [Website](https://azure.microsoft.com/en-us/products/functions) |
| Google Cloud Functions | GCP serverless functions | <kbd>🏷️ Multi-language</kbd> | [GitHub](https://github.com/GoogleCloudPlatform/functions-framework) • [Website](https://cloud.google.com/functions) |
| Cloudflare Workers | Edge serverless framework | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/cloudflare/workers-sdk) • [Website](https://workers.cloudflare.com) |
| Vercel Functions | Frontend serverless functions | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/vercel/vercel) • [Website](https://vercel.com/docs/functions) |
| Netlify Functions | JAMstack serverless functions | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/netlify/netlify-lambda) • [Website](https://docs.netlify.com/functions/overview/) |
| OpenFaaS | Open-source FaaS framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/openfaas/faas) • [Website](https://www.openfaas.com) |
| Knative | Kubernetes serverless framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/knative/serving) • [Website](https://knative.dev) |
| Fission | Kubernetes FaaS framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/fission/fission) • [Website](https://fission.io) |
| Fn Project | Oracle serverless framework | <kbd>🏷️ Multi-language</kbd> | [GitHub](https://github.com/fnproject/fn) • [Website](https://fnproject.io) |
| SST (Serverless Stack) | Full-stack serverless framework | <kbd>🏷️ TypeScript</kbd> | [GitHub](https://github.com/sst/sst) • [Website](https://sst.dev) |
| Architect | AWS serverless framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/architect/architect) • [Website](https://arc.codes) |

## Monitoring & Observability Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Prometheus | Metrics collection framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/prometheus/prometheus) • [Website](https://prometheus.io) |
| Grafana | Metrics visualization platform | <kbd>🏷️ JSON</kbd> | [GitHub](https://github.com/grafana/grafana) • [Website](https://grafana.com) |
| Datadog | Full-stack monitoring platform | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/DataDog/datadog-agent) • [Website](https://www.datadoghq.com) |
| New Relic | APM & observability platform | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/newrelic/newrelic-agent) • [Website](https://newrelic.com) |
| Dynatrace | AI-powered monitoring framework | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/Dynatrace/dynatrace-operator) • [Website](https://www.dynatrace.com) |
| Elastic Stack (ELK) | Log management & analytics | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/elastic/elasticsearch) • [Website](https://www.elastic.co/elastic-stack) |
| Jaeger | Distributed tracing framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/jaegertracing/jaeger) • [Website](https://www.jaegertracing.io) |
| Zipkin | Distributed tracing system | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/openzipkin/zipkin) • [Website](https://zipkin.io) |
| OpenTelemetry | Observability instrumentation framework | <kbd>🏷️ Multi</kbd> | [GitHub](https://github.com/open-telemetry/opentelemetry-specification) • [Website](https://opentelemetry.io) |
| Fluentd | Log collection framework | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/fluent/fluentd) • [Website](https://www.fluentd.org) |
| Logstash | Log processing pipeline | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/elastic/logstash) • [Website](https://www.elastic.co/logstash) |
| Loki | Log aggregation framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/grafana/loki) • [Website](https://grafana.com/oss/loki/) |
| Tempo | Distributed tracing backend | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/grafana/tempo) • [Website](https://grafana.com/oss/tempo/) |
| Victoria Metrics | High-performance metrics framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/VictoriaMetrics/VictoriaMetrics) • [Website](https://victoriametrics.com) |
| Thanos | Highly available Prometheus | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/thanos-io/thanos) • [Website](https://thanos.io) |
| Cortex | Horizontally scalable Prometheus | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/cortexproject/cortex) • [Website](https://cortexmetrics.io) |
| Netdata | Real-time monitoring framework | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/netdata/netdata) • [Website](https://www.netdata.cloud) |
| Zabbix | Enterprise monitoring framework | <kbd>🏷️ PHP</kbd> | [GitHub](https://github.com/zabbix/zabbix) • [Website](https://www.zabbix.com) |
| Nagios | IT infrastructure monitoring | <kbd>🏷️ PHP</kbd> | [GitHub](https://github.com/NagiosEnterprises/nagioscore) • [Website](https://www.nagios.org) |
| Checkmk | Hybrid IT monitoring framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/Checkmk/checkmk) • [Website](https://checkmk.com) |

## Service Mesh Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Istio | Service mesh for Kubernetes | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/istio/istio) • [Website](https://istio.io) |
| Linkerd | Lightweight service mesh | <kbd>🏷️ Rust</kbd> | [GitHub](https://github.com/linkerd/linkerd2) • [Website](https://linkerd.io) |
| Consul | HashiCorp service mesh | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/hashicorp/consul) • [Website](https://www.consul.io) |
| Envoy | High-performance proxy framework | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/envoyproxy/envoy) • [Website](https://www.envoyproxy.io) |
| Kuma | Universal service mesh | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/kumahq/kuma) • [Website](https://kuma.io) |
| AWS App Mesh | AWS service mesh framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/aws/aws-app-mesh-examples) • [Website](https://aws.amazon.com/app-mesh/) |
| NGINX Service Mesh | NGINX-based service mesh | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/nginxinc/nginx-service-mesh) • [Website](https://www.nginx.com/products/nginx-service-mesh/) |
| Traefik Mesh | Simple Kubernetes service mesh | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/traefik/mesh) • [Website](https://traefik.io/traefik-mesh/) |
| Open Service Mesh | Microsoft open service mesh | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/openservicemesh/osm) • [Website](https://openservicemesh.io) |
| Cilium | eBPF-based networking & security | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/cilium/cilium) • [Website](https://cilium.io) |

## Security & Compliance Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Vault | HashiCorp secrets management | <kbd>🏷️ HCL</kbd> | [GitHub](https://github.com/hashicorp/vault) • [Website](https://www.vaultproject.io) |
| Cert-Manager | Kubernetes TLS certificate manager | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/cert-manager/cert-manager) • [Website](https://cert-manager.io) |
| Falco | Runtime security monitoring | <kbd>🏷️ C++</kbd> | [GitHub](https://github.com/falcosecurity/falco) • [Website](https://falco.org) |
| OPA (Open Policy Agent) | Policy as code framework | <kbd>🏷️ Rego</kbd> | [GitHub](https://github.com/open-policy-agent/opa) • [Website](https://www.openpolicyagent.org) |
| Kyverno | Kubernetes policy engine | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/kyverno/kyverno) • [Website](https://kyverno.io) |
| Trivy | Container vulnerability scanner | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/aquasecurity/trivy) • [Website](https://trivy.dev) |
| Snyk | Developer security framework | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/snyk/cli) • [Website](https://snyk.io) |
| Aqua Security | Cloud-native security platform | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/aquasecurity) • [Website](https://www.aquasec.com) |
| Twistlock | Container security framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/twistlock) • [Website](https://www.paloaltonetworks.com/prisma/cloud) |
| Sysdig | Cloud-native security & monitoring | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/draios/sysdig) • [Website](https://sysdig.com) |
| RBAC | Kubernetes role-based access control | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/kubernetes/kubernetes) • [Website](https://kubernetes.io/docs/reference/access-authn-authz/rbac/) |
| AWS IAM | AWS identity & access management | <kbd>🏷️ JSON</kbd> | [GitHub](https://github.com/aws/aws-sdk-go-v2) • [Website](https://aws.amazon.com/iam/) |
| Azure AD | Microsoft identity framework | <kbd>🏷️ JSON</kbd> | [GitHub](https://github.com/AzureAD/microsoft-authentication-library-for-js) • [Website](https://azure.microsoft.com/en-us/products/active-directory) |
| SonarQube | Code quality & security scanner | <kbd>🏷️ XML</kbd> | [GitHub](https://github.com/SonarSource/sonarqube) • [Website](https://www.sonarsource.com/products/sonarqube/) |
| Checkov | IaC security scanning framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/bridgecrewio/checkov) • [Website](https://www.checkov.io) |

## GitOps Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| ArgoCD | Declarative GitOps for Kubernetes | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/argoproj/argo-cd) • [Website](https://argo-cd.readthedocs.io) |
| Flux | GitOps toolkit for Kubernetes | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/fluxcd/flux2) • [Website](https://fluxcd.io) |
| Weave GitOps | Enterprise GitOps framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/weaveworks/weave-gitops) • [Website](https://www.weave.works/product/gitops/) |
| Rancher Fleet | Multi-cluster GitOps framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/rancher/fleet) • [Website](https://fleet.rancher.io) |
| Jenkins X | Cloud-native CI/CD & GitOps | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/jenkins-x/jx) • [Website](https://jenkins-x.io) |
| Spinnaker | Multi-cloud GitOps delivery | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/spinnaker/spinnaker) • [Website](https://spinnaker.io) |
| PipeCD | Unified GitOps CD framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/pipe-cd/pipecd) • [Website](https://pipecd.dev) |
| Codefresh | GitOps CI/CD platform | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/codefresh-io/cli) • [Website](https://codefresh.io) |
| Atlantis | Terraform GitOps automation | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/runatlantis/atlantis) • [Website](https://www.runatlantis.io) |
| Digger | IaC GitOps orchestrator | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/diggerhq/digger) • [Website](https://digger.dev) |

## Cloud Networking Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Calico | Kubernetes network security | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/projectcalico/calico) • [Website](https://www.tigera.io/project-calico/) |
| Flannel | Kubernetes overlay network | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/flannel-io/flannel) • [Website](https://github.com/flannel-io/flannel) |
| Weave Net | Kubernetes networking framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/weaveworks/weave) • [Website](https://www.weave.works/oss/net/) |
| Cilium | eBPF Kubernetes networking | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/cilium/cilium) • [Website](https://cilium.io) |
| Multus | Multi-network Kubernetes plugin | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/k8snetworkplumbingwg/multus-cni) • [Website](https://github.com/k8snetworkplumbingwg/multus-cni) |
| MetalLB | Bare-metal load balancer | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/metallb/metallb) • [Website](https://metallb.universe.tf) |
| Nginx Ingress | Kubernetes ingress controller | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/kubernetes/ingress-nginx) • [Website](https://kubernetes.github.io/ingress-nginx/) |
| Traefik | Cloud-native edge router | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/traefik/traefik) • [Website](https://traefik.io) |
| HAProxy | High-availability load balancer | <kbd>🏷️ C</kbd> | [GitHub](https://github.com/haproxy/haproxy) • [Website](https://www.haproxy.org) |
| AWS VPC | Amazon virtual private cloud | <kbd>🏷️ JSON</kbd> | [GitHub](https://github.com/aws/aws-vpc-cni-k8s) • [Website](https://aws.amazon.com/vpc/) |
| Terraform VPC | VPC infrastructure automation | <kbd>🏷️ HCL</kbd> | [GitHub](https://github.com/terraform-aws-modules/terraform-aws-vpc) • [Website](https://registry.terraform.io/modules/terraform-aws-modules/vpc/aws/) |
| Submariner | Multi-cluster Kubernetes networking | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/submariner-io/submariner) • [Website](https://submariner.io) |

## Cloud Cost Management Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Infracost | IaC cloud cost estimation | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/infracost/infracost) • [Website](https://www.infracost.io) |
| CloudHealth | Multi-cloud cost management | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/vmware/cloudhealth-tools) • [Website](https://cloudhealth.vmware.com) |
| Spot.io | Cloud cost optimization platform | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/spotinst) • [Website](https://spot.io) |
| Kubecost | Kubernetes cost monitoring | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/kubecost/cost-model) • [Website](https://www.kubecost.com) |
| OpenCost | Open-source Kubernetes cost | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/opencost/opencost) • [Website](https://www.opencost.io) |
| AWS Cost Explorer | AWS cost analysis framework | <kbd>🏷️ JSON</kbd> | [GitHub](https://github.com/aws-samples/aws-cost-explorer-report) • [Website](https://aws.amazon.com/aws-cost-management/aws-cost-explorer/) |
| Azure Cost Management | Azure cost optimization | <kbd>🏷️ JSON</kbd> | [GitHub](https://github.com/Azure/CCODashboard) • [Website](https://azure.microsoft.com/en-us/products/cost-management) |
| Google Cloud Billing | GCP billing management | <kbd>🏷️ JSON</kbd> | [GitHub](https://github.com/GoogleCloudPlatform/billing-budget-api-sample) • [Website](https://cloud.google.com/billing) |
| Apptio Cloudability | FinOps cloud cost platform | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/apptio) • [Website](https://www.apptio.com/products/cloudability/) |
| CloudZero | Cloud cost intelligence platform | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/Cloudzero) • [Website](https://www.cloudzero.com) |

## DevOps Testing Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| Terratest | Infrastructure testing framework | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/gruntwork-io/terratest) • [Website](https://terratest.gruntwork.io) |
| Kitchen-Terraform | Terraform test framework | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/newcontext-oss/kitchen-terraform) • [Website](https://github.com/newcontext-oss/kitchen-terraform) |
| Molecule | Ansible role testing framework | <kbd>🏷️ Python</kbd> | [GitHub](https://github.com/ansible-community/molecule) • [Website](https://molecule.readthedocs.io) |
| Inspec | Infrastructure compliance testing | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/inspec/inspec) • [Website](https://www.inspec.io) |
| Serverspec | Server configuration testing | <kbd>🏷️ Ruby</kbd> | [GitHub](https://github.com/mizzy/serverspec) • [Website](https://serverspec.org) |
| Goss | Quick server validation tool | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goss-org/goss) • [Website](https://goss.rocks) |
| KUTTL | Kubernetes testing framework | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/kudobuilder/kuttl) • [Website](https://kuttl.dev) |
| Chaos Monkey | Netflix resilience testing | <kbd>🏷️ Java</kbd> | [GitHub](https://github.com/Netflix/chaosmonkey) • [Website](https://netflix.github.io/chaosmonkey/) |
| Litmus | Kubernetes chaos engineering | <kbd>🏷️ YAML</kbd> | [GitHub](https://github.com/litmuschaos/litmus) • [Website](https://litmuschaos.io) |
| Chaos Mesh | Cloud-native chaos engineering | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/chaos-mesh/chaos-mesh) • [Website](https://chaos-mesh.org) |
| Gremlin | Enterprise chaos engineering | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/gremlin/gremlin-python) • [Website](https://www.gremlin.com) |
| Toxiproxy | Network condition testing | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/Shopify/toxiproxy) • [Website](https://github.com/Shopify/toxiproxy) |

## Artifact & Registry Frameworks

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|
| JFrog Artifactory | Universal artifact repository | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/jfrog/artifactory-oss) • [Website](https://jfrog.com/artifactory/) |
| Nexus Repository | Artifact management platform | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/sonatype/nexus-public) • [Website](https://www.sonatype.com/products/sonatype-nexus-repository) |
| Docker Hub | Container image registry | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/docker/hub-feedback) • [Website](https://hub.docker.com) |
| GitHub Container Registry | GitHub image registry | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/features/packages) • [Website](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry) |
| AWS ECR | Amazon container registry | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/aws/amazon-ecr-credential-helper) • [Website](https://aws.amazon.com/ecr/) |
| Azure Container Registry | Microsoft container registry | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/Azure/acr) • [Website](https://azure.microsoft.com/en-us/products/container-registry) |
| Google Artifact Registry | GCP artifact management | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/GoogleCloudPlatform/artifact-registry-apt-transport) • [Website](https://cloud.google.com/artifact-registry) |
| Harbor | Open-source container registry | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/goharbor/harbor) • [Website](https://goharbor.io) |
| Quay.io | Red Hat container registry | <kbd>🏷️ CLI</kbd> | [GitHub](https://github.com/quay/quay) • [Website](https://quay.io) |
| Chartmuseum | Helm chart repository | <kbd>🏷️ Go</kbd> | [GitHub](https://github.com/helm/chartmuseum) • [Website](https://chartmuseum.com) |