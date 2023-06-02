# DevOps &amp; SRE Library

A library of articles and tools bookmarked by me for the years of working with DevOps practises.

Table of content:

* [Architecture](#Architecture)

* [AWESOME lists and CheatSheets](#AWESOME-lists-and-CheatSheets)

* [Cloudnative](#Cloudnative)

* [Kubernetes general](#Kubernetes-general)

* [Kubernetes Operators and AddOns](#Kubernetes-Operators-and-AddOns)

* [CI/CD and IaC](#CI/CD-and-IaC)

* [Observability](#Observability)

* [Security](#Security)

* [SRE](#SRE)

* [Serverless](#Serverless)

* [Software Development](#Software-Development)

* [Unsorted](#Unsorted)

## Architecture

How Kafka and Redis Solve Stream-Processing Challenges – The New Stack [thenewstack.io](https://thenewstack.io/how-kafka-and-redis-solve-stream-processing-challenges/)

How to create a financial marketplace for 500,000 people 💸. Part II (technical) [hackernoon.com](https://hackernoon.com/how-to-create-a-financial-marketplace-for-500-000-people-part-ii-technical-4d2456d9768d)

Kubernetes Multi-Tenancy: Why Virtual Clusters Are The Best Solution | Loft Blog [loft.sh](https://loft.sh/blog/kubernetes-multi-tenancy-why-virtual-clusters-are-the-best-solution/)

Manage AWS Accounts Using Control Tower Account Factory for Terraform | Terraform - HashiCorp Learn [learn.hashicorp.com](https://learn.hashicorp.com/tutorials/terraform/aws-control-tower-aft)

5 patterns to make your microservice fault-tolerant [itnext.io](https://itnext.io/5-patterns-to-make-your-microservice-fault-tolerant-f3a1c73547b3)

The Big Little Guide to Message Queues [sudhir.io](https://sudhir.io/the-big-little-guide-to-message-queues/)




## AWESOME lists and CheatSheets

awesome-kubernetes/README.md at master · ramitsurana/awesome-kubernetes · GitHub [github.com](https://github.com/ramitsurana/awesome-kubernetes/blob/master/README.md)

Awesome Prometheus alerts | Collection of alerting rules [awesome-prometheus-alerts.grep.to](https://awesome-prometheus-alerts.grep.to/)

GitHub - magsther/awesome-opentelemetry: A curated list of OpenTelemetry resources [github.com](https://github.com/magsther/awesome-opentelemetry#exporters)

PromLabs | PromQL Cheat Sheet [promlabs.com](https://promlabs.com/promql-cheat-sheet/)

Tables - Postgres Cheatsheet [postgrescheatsheet.com](https://postgrescheatsheet.com/#/tables)

The Illustrated TLS Connection: Every Byte Explained [tls.ulfheim.net](https://tls.ulfheim.net/)




## Cloudnative

ClusterAPI — A Guide on How to Get Started - Product Development at Condé Nast International - Medium [medium.com](https://medium.com/condenastengineering/clusterapi-a-guide-on-how-to-get-started-ff9a81262945)

Amazon.com: Cloud Native DevOps with Kubernetes: Building, Deploying, and Scaling Modern Applications in the Cloud (9781492040767): John Arundel, Justin Domingus: Books [www.amazon.com](https://www.amazon.com/Cloud-Native-DevOps-Kubernetes-Applications/dp/1492040762)

How to deploy a production-grade Kubernetes cluster on AWS [gruntwork.io](https://gruntwork.io/guides/kubernetes/how-to-deploy-production-grade-kubernetes-cluster-aws#updating-the-worker-nodes)

How to deploy a production-grade VPC on AWS [gruntwork.io](https://gruntwork.io/guides/networking/how-to-deploy-production-grade-vpc-aws#default_vpcs_custom_vpcs)

CloudFormation Ref and GetAtt cheatsheet | theburningmonk.com [theburningmonk.com](https://theburningmonk.com/cloudformation-ref-and-getatt-cheatsheet/)



GitHub - iann0036/iamlive: Generate a basic IAM policy from AWS client-side monitoring (CSM) [github.com](https://github.com/iann0036/iamlive)

GitHub - elpy1/ssh-over-ssm: SSH over AWS SSM. No bastions or public-facing instances. SSH user management through IAM. No requirement to store SSH keys locally or on server. [github.com](https://github.com/elpy1/ssh-over-ssm)




## Kubernetes general

User and workload identities in Kubernetes [learnk8s.io](https://learnk8s.io/authentication-kubernetes)

Kubernetes Network Plugins - kubedex.com [kubedex.com](https://kubedex.com/kubernetes-network-plugins/)

Kubernetes: жизнь пода / Хабр [m.habr.com](https://m.habr.com/company/flant/blog/415393/)

Почему в Kubernetes так сложно с хранилищами? / Хабр [m.habr.com](https://m.habr.com/ru/post/441222/)

За кулисами сети в Kubernetes / Хабр [m.habr.com](https://m.habr.com/company/flant/blog/420813/?utm_content=link2post)

Локальные файлы при переносе приложения в Kubernetes / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/471582/?utm_content=link2post)

Масштабируем Kubernetes до 4000+ нод и 200 000 подов / Хабр [habr.com](https://habr.com/ru/company/southbridge/blog/651435/)

Из жизни с Kubernetes: Как мы выносили СУБД (и не только) из review-окружений в статическое / Блог компании Флант / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/501424/)

Kube-fledged: Cache Container Images in Kubernetes | by Senthil Raja Chermapandian | Sep, 2021 | ITNEXT [itnext.io](https://itnext.io/kube-fledged-cache-container-images-in-kubernetes-7880a00bab91)

Kubernetes Multicluster with Kind and Cilium - Piotr's TechBlog [piotrminkowski.com](https://piotrminkowski.com/2021/10/25/kubernetes-multicluster-with-kind-and-cilium/)



GitHub - diegolnasc/kubernetes-best-practices: A cookbook with the best practices to working with kubernetes. [github.com](https://github.com/diegolnasc/kubernetes-best-practices)

GitHub - wencaiwulue/kubevpn: KubeVPN, A vpn tunnel tools which can connect to kubernetes cluster network, you can access remote kubernetes cluster network, remote kubernetes cluster service can also access your local service [github.com](https://github.com/wencaiwulue/kubevpn)

GitHub - loft-sh/vcluster: vcluster - Create fully functional virtual Kubernetes clusters - Each vcluster runs inside a namespace of the underlying k8s cluster. It's cheaper than creating separate full-blown clusters and it offers better multi-tenancy and isolation than regular namespaces. [github.com](https://github.com/loft-sh/vcluster)

GitHub - utkuozdemir/pv-migrate: Persistent volume migration plugin for Kubernetes [github.com](https://github.com/utkuozdemir/pv-migrate)

kops/README.md at master · kubernetes/kops · GitHub [github.com](https://github.com/kubernetes/kops/blob/master/README.md)




## Kubernetes Operators and AddOns

OpenTelemetry Operator. Tracing made easy | by Magsther | Mar, 2023 | Medium [medium.com](https://medium.com/@magstherdev/opentelemetry-operator-d3d407354cbf)

Comparing Kubernetes operators for PostgreSQL – Flant blog [blog.flant.com](https://blog.flant.com/comparing-kubernetes-operators-for-postgresql/)


Mutating Kubernetes resources with Gatekeeper | by Lachlan Evenson | Aug, 2021 | Medium [medium.com](https://medium.com/@LachlanEvenson/mutating-kubernetes-resources-with-gatekeeper-3e5585d49ead)

Представляем shell-operator: создавать операторы для Kubernetes стало ещё проще / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/447442/?utm_content=link2post)

Обзор и сравнение контроллеров Ingress для Kubernetes / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/447180/?utm_content=link2post)

Kubernetes Ingress Controllers: How to choose the right one: Part 1 [itnext.io](https://itnext.io/kubernetes-ingress-controllers-how-to-choose-the-right-one-part-1-41d3554978d2)



GitHub - jodevsa/wireguard-operator: A wireguard operator created to easily provision a VPN in a k8s cluster [github.com](https://github.com/jodevsa/wireguard-operator)

GitHub - k8spin/k8spin-operator: K8Spin multi-tenant operator - OSS [github.com](https://github.com/k8spin/k8spin-operator)

haproxy-ingress/README.md at master · jcmoraisjr/haproxy-ingress · GitHub [github.com](https://github.com/jcmoraisjr/haproxy-ingress/blob/master/examples/deployment/README.md)

GitHub - AbsaOSS/k8gb: A cloud native Kubernetes Global Balancer [github.com](https://github.com/AbsaOSS/k8gb)




## CI/CD and IaC

Flux from End-to-End | Flux [fluxcd.io](https://fluxcd.io/docs/flux-e2e/)

Real-World GitOps with Flux, Flagger, and Linkerd | Linkerd [linkerd.io](https://linkerd.io/2023/05/15/real-world-gitops/index.html)

Four Great Alternatives to HashiCorp’s Terraform Cloud | by Elliot Graebert | Jul, 2022 | Medium [medium.com](https://medium.com/@elliotgraebert/four-great-alternatives-to-hashicorps-terraform-cloud-6e0a3a0a5482)

Deploys at Slack - Several People Are Coding [slack.engineering](https://slack.engineering/deploys-at-slack-cd0d28c61701)

20 Terraform Best Practices to Create Clean and Reusable Code | Contino | Global Transformation Consultancy [www.contino.io](https://www.contino.io/insights/terraform-best-practices)

The “Best” Terraform CD pipeline with GitHub Actions | by Sam Gallagher | Jan, 2023 | Medium [medium.com](https://medium.com/@gallaghersam95/the-best-terraform-cd-pipeline-with-github-actions-6ecbaa5f3762)

Lessons learned from 100s of Infrastructure as Code (IaC) setups | Sören Martius [platformengineering.org](https://platformengineering.org/talks-library/infrastructure-as-code-setups)

Как сделать ваши GitLab CI пайплайны быстрее / Хабр [habr.com](https://habr.com/ru/company/gitlab/blog/646579/)

Лучшие практики для деплоя высокодоступных приложений в Kubernetes. Часть 1 / Флант / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/545204/)

Deploying artifacts to Maven using Gradle – .debug – Medium [medium.com](https://medium.com/dot-debug/deploying-artifacts-to-maven-using-gradle-b669acc1b6f8)

Don't Put Fat Jars in Docker Images [phauer.com](https://phauer.com/2019/no-fat-jar-in-docker-image/)



GitHub - uber/kraken: P2P Docker registry capable of distributing TBs of data in seconds [github.com](https://github.com/uber/kraken)

GitHub - pipe-cd/pipe: Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications [github.com](https://github.com/pipe-cd/pipe)

GitHub - stefanprodan/gitops-istio: GitOps Progressive Delivery demo with Istio, Flux, Helm Operator and Flagger [github.com](https://github.com/stefanprodan/gitops-istio)

Guide | Keel [keel.sh](https://keel.sh/docs/#deploying-with-helm)

GitHub - valentindeaconu/terralist: A private Terraform registry [github.com](https://github.com/valentindeaconu/terralist)

GitHub - dineshba/tf-summarize: A command-line utility to print the summary of the terraform plan [github.com](https://github.com/dineshba/tf-summarize)

GitHub - vmware-tanzu/buildkit-cli-for-kubectl: BuildKit CLI for kubectl is a tool for building container images with your Kubernetes cluster [github.com](https://github.com/vmware-tanzu/buildkit-cli-for-kubectl)

GitHub - docker-slim/docker-slim: DockerSlim (docker-slim): Don't change anything in your Docker container image and minify it by up to 30x (and for compiled languages even more) making it secure too! (free and open source) [github.com](https://github.com/docker-slim/docker-slim)




## Observability

Deploying a Modern Monitoring Stack (Part 1) | by Caoimhe Harvey | Dev Genius [blog.devgenius.io](https://blog.devgenius.io/deploying-a-modern-monitoring-stack-part-1-5eb8ada105ba)

How to Build an End to End Open Source Observability Solution on Kubernetes | by Eden Federman | Aug, 2022 | Medium [medium.com](https://medium.com/@edeNFed/how-to-build-an-end-to-end-open-source-observability-solution-on-kubernetes-c8725c016dd5)

Multi-Cluster Monitoring with Thanos [particule.io](https://particule.io/en/blog/thanos-monitoring/)

17 DevOps Metrics To Measure Success | by Semaphore | Medium [semaphoreci.medium.com](https://semaphoreci.medium.com/17-devops-metrics-to-measure-success-cca66a9e79c)

6 Metrics to Watch for on Your K8s Cluster | by Erez Rabih | May, 2022 | Medium [erezrabih.medium.com](https://erezrabih.medium.com/6-metrics-to-watch-for-on-your-k8s-cluster-76d58f08397f)

USE vs RED vs The Four Golden Signals | by Magsther | FAUN Publication [medium.com](https://medium.com/faun/use-vs-red-vs-the-four-golden-signals-50655e93fad7)

Top key metrics for monitoring MySQL – Sysdig [sysdig.com](https://sysdig.com/blog/mysql-monitoring/)

Elasticsearch Performance Tuning Practice at eBay [www.ebayinc.com](https://www.ebayinc.com/stories/blogs/tech/elasticsearch-performance-tuning-practice-at-ebay/)

Parsing SSH Logs with Grafana Loki [voidquark.com](https://voidquark.com/parsing-ssh-logs-with-grafana-loki/)

BotKube :: Messaging bot for monitoring and debugging Kubernetes clusters [www.botkube.io](https://www.botkube.io/)

PromQL for Humans [timber.io](https://timber.io/blog/promql-for-humans/#offset)

Using Environment Variables for Configuration, Provisioning, and Dashboards in Grafana | by Mikhail Volkov | Feb, 2022 | Volkov Labs [volkovlabs.com](https://volkovlabs.com/using-environment-variables-for-configuration-provisioning-and-dashboards-in-grafana-279661733416)



GitHub - dotdc/grafana-dashboards-kubernetes: A set of modern Grafana dashboards for Kubernetes. [github.com](https://github.com/dotdc/grafana-dashboards-kubernetes)

query-exporter/query_exporter at master · albertodonato/query-exporter · GitHub [github.com](https://github.com/albertodonato/query-exporter/tree/master/query_exporter)

GitHub - prymitive/karma: Alert dashboard for Prometheus Alertmanager [github.com](https://github.com/prymitive/karma)

GitHub - prabhatsharma/zinc: Zinc Search engine. A lightweight alternative to elasticsearch that requires minimal resources, written in Go. [github.com](https://github.com/prabhatsharma/zinc)

GitHub - TwinProduction/gatus: ⛑ Gatus - Automated service health dashboard [github.com](https://github.com/TwinProduction/gatus)

GitHub - kinvolk/inspektor-gadget: Collection of gadgets for debugging and introspecting Kubernetes applications using BPF [github.com](https://github.com/kinvolk/inspektor-gadget)

GitHub - idealista/prom2teams: prom2teams is an HTTP server built with Python that receives alert notifications from a previously configured Prometheus Alertmanager instance and forwards it to Microsoft Teams using defined connectors [github.com](https://github.com/idealista/prom2teams)

GitHub - SigNoz/signoz: SigNoz is an open-source APM. It helps developers monitor their applications & troubleshoot problems, an open-source alternative to DataDog, NewRelic, etc. 🔥 🖥. 👉 Open source Application Performance Monitoring (APM) & Observability tool [github.com](https://github.com/signoz/signoz)




## Security

A Secure Cloud [asecure.cloud](https://asecure.cloud/)

OWASP Top 10 CI/CD Security Risks | OWASP Foundation [owasp.org](https://owasp.org/www-project-top-10-ci-cd-security-risks/?utm_source=telegram&utm_medium=deflope&utm_campaign=-1001033513075&utm_term=2022_12_19_10_50&utm_content=292896753)

Top 20 Dockerfile best practices for security | Sysdig [sysdig.com](https://sysdig.com/blog/dockerfile-best-practices/)

5 best practices to get to production readiness with Hashicorp Vault in Kubernetes - Expel [expel.io](https://expel.io/blog/production-readiness-hashicorp-vault-kubernetes/)



GitHub - deepfence/SecretScanner: Find secrets and passwords in container images and file systems [github.com](https://github.com/deepfence/SecretScanner)

GitHub - fivexl/aws-ecr-client-golang: AWS ECR client to automated push to ECR and handling of vulnerability [github.com](https://github.com/fivexl/aws-ecr-client-golang)

GitHub - toniblyx/my-arsenal-of-aws-security-tools: List of open source tools for AWS security: defensive, offensive, auditing, DFIR, etc. [github.com](https://github.com/toniblyx/my-arsenal-of-aws-security-tools)




## SRE

A Step-by-Step Guide to Calculate SLAs, SLIs, and SLOs for Your IT Services | by Abhishek Gupta | Mar, 2023 | AceTheCloud [blog.acethecloud.com](https://blog.acethecloud.com/a-step-by-step-guide-to-calculating-slas-slis-and-slos-for-your-it-services-6f0a07b67bb5)

Availability window, SRE [landing.google.com](https://landing.google.com/sre/book/chapters/availability-table.html#appendix_table-of-nines)

SREcon: Performance Checklists for SREs 2016 [www.brendangregg.com](https://www.brendangregg.com/blog/2016-05-04/srecon2016-perf-checklists-for-sres.html)




## Serverless

Serverless Framework vs SAM vs AWS CDK [tastefulelk.hashnode.dev](https://tastefulelk.hashnode.dev/serverless-framework-vs-sam-vs-aws-cdk)

Serverless patterns | Serverless Land [serverlessland.com](https://serverlessland.com/patterns)

Introducing AWS SAM Pipelines: Automatically generate deployment pipelines for serverless applications | AWS Compute Blog [aws.amazon.com](https://aws.amazon.com/blogs/compute/introducing-aws-sam-pipelines-automatically-generate-deployment-pipelines-for-serverless-applications/)




## Software Development

GitHub - benkehoe/aws-assume-role-lib: Assumed role session chaining (with credential refreshing) for boto3 [github.com](https://github.com/benkehoe/aws-assume-role-lib)

Interprocess communication in Python - Stack Overflow [stackoverflow.com](https://stackoverflow.com/questions/6920858/interprocess-communication-in-python)

Signals and Slots (registering callbacks) — Pizco 0.1 documentation [pizco.readthedocs.io](https://pizco.readthedocs.io/en/latest/signals.html)

A guide to Python's function decorators [www.thecodeship.com](https://www.thecodeship.com/patterns/guide-to-python-function-decorators/)

Учебник – Нейронные сети [neuralnet.info](https://neuralnet.info/book/)

An A-Z of useful Python tricks – freeCodeCamp [medium.freecodecamp.org](https://medium.freecodecamp.org/an-a-z-of-useful-python-tricks-b467524ee747)

How to completely traverse a complex dictionary of unknown depth? - Stack Overflow [stackoverflow.com](https://stackoverflow.com/questions/12507206/how-to-completely-traverse-a-complex-dictionary-of-unknown-depth)




## Unsorted

gort/README.md at master · idestis/gort · GitHub [github.com](https://github.com/idestis/gort/blob/master/README.md)

GitHub - Yelp/dumb-init: A minimal init system for Linux containers [github.com](https://github.com/yelp/dumb-init)

Maven Publish Plugin [docs.gradle.org](https://docs.gradle.org/current/userguide/publishing_maven.html)

Caddy - The HTTP/2 Web Server with Automatic HTTPS [caddyserver.com](https://caddyserver.com/)

bpftrace (DTrace 2.0) for Linux 2018 [www.brendangregg.com](http://www.brendangregg.com/blog/2018-10-08/dtrace-for-linux-2018.html)

GitHub - tomav/docker-mailserver: A fullstack but simple mailserver (smtp, imap, antispam, antivirus, ssl...) using Docker. [github.com](https://github.com/tomav/docker-mailserver)

GitHub - flant/ovpn-admin: Simple web UI to manage OpenVPN users. [github.com](https://github.com/flant/ovpn-admin)

GitHub - fabianlindfors/reshape: An easy-to-use, zero-downtime schema migration tool for Postgres [github.com](https://github.com/fabianlindfors/reshape)

Экстремальная настройка производительности HTTP: 1,2M API RPS на инстансе EC2 с 4 виртуальными процессорами (vCPU) / Хабр [habr.com](https://habr.com/ru/company/flant/blog/651867/)

GitHub - xo/usql: Universal command-line interface for SQL databases [github.com](https://github.com/xo/usql)

GitHub - readysettech/readyset: ReadySet is a lightweight SQL caching engine written in Rust that helps developers enhance the performance and scalability of existing applications. [github.com](https://github.com/readysettech/readyset)

GitHub - kellyjonbrazil/jc: CLI tool and python library that converts the output of popular command-line tools, file-types, and common strings to JSON, YAML, or Dictionaries. This allows piping of output to tools like jq and simplifying automation scripts. [github.com](https://github.com/kellyjonbrazil/jc)
