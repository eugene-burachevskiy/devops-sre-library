# DevOps &amp; SRE Library

A library of articles and tools bookmarked by me for the years of working with DevOps practises.

Table of content:

* [Architecture](#Architecture)

* [AWESOME lists and CheatSheets](#AWESOME-lists-and-CheatSheets)

* [Cloudnative](#Cloudnative)

* [Kubernetes general](#Kubernetes-general)

* [Kubernetes Operators and AddOns](#Kubernetes-Operators-and-AddOns)

* [CI/CD and IaC](#CICD-and-IaC)

* [Observability](#Observability)

* [Security](#Security)

* [SRE](#SRE)

* [Serverless](#Serverless)

* [Software Development](#Software-Development)

* [Unsorted](#Unsorted)

## Architecture

Designing WhatsApp - High Scalability - [highscalability.com](http://highscalability.com/blog/2022/1/3/designing-whatsapp.html)

Designing Netflix - High Scalability - [highscalability.com](http://highscalability.com/blog/2021/12/13/designing-netflix.html)

How Kafka and Redis Solve Stream-Processing Challenges – The New Stack [thenewstack.io](https://thenewstack.io/how-kafka-and-redis-solve-stream-processing-challenges/)

5 patterns to make your microservice fault-tolerant [itnext.io](https://itnext.io/5-patterns-to-make-your-microservice-fault-tolerant-f3a1c73547b3)

The Big Little Guide to Message Queues [sudhir.io](https://sudhir.io/the-big-little-guide-to-message-queues/)

How to create a financial marketplace for 500,000 people 💸. Part II (technical) [hackernoon.com](https://hackernoon.com/how-to-create-a-financial-marketplace-for-500-000-people-part-ii-technical-4d2456d9768d)

sergiomarotco/Network-segmentation-cheat-sheet: Best practices for segmentation of the corporate network of any company [github.com](https://github.com/sergiomarotco/Network-segmentation-cheat-sheet?utm_source=telegram.me&utm_medium=social&utm_campaign=opisanie-luchshih-praktik-planirovaniya-set)

Event-Driven Data Management for Microservices - NGINX [www.nginx.com](https://www.nginx.com/blog/event-driven-data-management-microservices/)

Overview of Data Transfer Costs for Common Architectures | AWS Architecture Blog [aws.amazon.com](https://aws.amazon.com/blogs/architecture/overview-of-data-transfer-costs-for-common-architectures/)

Manage AWS Accounts Using Control Tower Account Factory for Terraform | Terraform - HashiCorp Learn [learn.hashicorp.com](https://learn.hashicorp.com/tutorials/terraform/aws-control-tower-aft)

Books for Software Architects [vvsevolodovich.dev](https://vvsevolodovich.dev/books-for-software-architect/)

Чек-лист микросервисной архитектуры | Игорь Беспальчук [bespalchuk.ru](https://bespalchuk.ru/%d1%87%d0%b5%d0%ba-%d0%bb%d0%b8%d1%81%d1%82-%d0%bc%d0%b8%d0%ba%d1%80%d0%be%d1%81%d0%b5%d1%80%d0%b2%d0%b8%d1%81%d0%bd%d0%be%d0%b9-%d0%b0%d1%80%d1%85%d0%b8%d1%82%d0%b5%d0%ba%d1%82%d1%83%d1%80%d1%8b/)



## AWESOME lists and CheatSheets

Awesome Kubernetes Resources [github.com](https://github.com/tomhuang12/awesome-k8s-resources)

Awesome Prometheus alerts | Collection of alerting rules [awesome-prometheus-alerts.grep.to](https://awesome-prometheus-alerts.grep.to/)

CHECKLIST - Kubernetes production best practices [learnk8s.io](https://learnk8s.io/production-best-practices)

Kubernetes instance calculator [learnk8s.io](https://learnk8s.io/kubernetes-instance-calculator)

GitHub - magsther/awesome-opentelemetry: A curated list of OpenTelemetry resources [github.com](https://github.com/magsther/awesome-opentelemetry#exporters)

PromLabs | PromQL Cheat Sheet [promlabs.com](https://promlabs.com/promql-cheat-sheet/)

Tables - Postgres Cheatsheet [postgrescheatsheet.com](https://postgrescheatsheet.com/#/tables)

The Illustrated TLS Connection: Every Byte Explained [tls.ulfheim.net](https://tls.ulfheim.net/)




## Cloudnative

Overview - Amazon EKS Blueprints for Terraform [aws-ia.github.io](https://aws-ia.github.io/terraform-aws-eks-blueprints/v4.32.0/add-ons/)

ClusterAPI — A Guide on How to Get Started - Product Development at Condé Nast International - Medium [medium.com](https://medium.com/condenastengineering/clusterapi-a-guide-on-how-to-get-started-ff9a81262945)

Amazon.com: Cloud Native DevOps with Kubernetes: Building, Deploying, and Scaling Modern Applications in the Cloud (9781492040767): John Arundel, Justin Domingus: Books [www.amazon.com](https://www.amazon.com/Cloud-Native-DevOps-Kubernetes-Applications/dp/1492040762)

How to deploy a production-grade Kubernetes cluster on AWS [gruntwork.io](https://gruntwork.io/guides/kubernetes/how-to-deploy-production-grade-kubernetes-cluster-aws#updating-the-worker-nodes)

How to deploy a production-grade VPC on AWS [gruntwork.io](https://gruntwork.io/guides/networking/how-to-deploy-production-grade-vpc-aws#default_vpcs_custom_vpcs)

CloudFormation Ref and GetAtt cheatsheet | theburningmonk.com [theburningmonk.com](https://theburningmonk.com/cloudformation-ref-and-getatt-cheatsheet/)

Cloud config examples — Cloud-Init 0.7.9 documentation [cloudinit.readthedocs.io](http://cloudinit.readthedocs.io/en/latest/topics/examples.html#including-users-and-groups)

Azure AD as OIDC identity provider authentication for Amazon EKS | by Rahmat Fedayizada | Medium [fedayizada.medium.com](https://fedayizada.medium.com/using-azure-ad-as-oidc-identity-provider-authentication-for-amazon-eks-b75f5b2a4155)

AWS EKS authentification, aws-iam-authenticator, and AWS IAM | by Arseny Zinchenko (setevoy) | ITNEXT [itnext.io](https://itnext.io/kubernetes-part-4-aws-eks-authentification-aws-iam-authenticator-and-aws-iam-5985d5af9317)

EC2 EBS-SSD vs instance-store performance [gist.github.com](https://gist.github.com/ktheory/3c3616fca42a3716346b)

How to use AWS Secrets & Configuration Provider with your Kubernetes Secrets Store CSI driver | AWS Security Blog [aws.amazon.com](https://aws.amazon.com/blogs/security/how-to-use-aws-secrets-configuration-provider-with-kubernetes-secrets-store-csi-driver/)


GitHub - iann0036/iamlive: Generate a basic IAM policy from AWS client-side monitoring (CSM) [github.com](https://github.com/iann0036/iamlive)

GitHub - elpy1/ssh-over-ssm: SSH over AWS SSM. No bastions or public-facing instances. SSH user management through IAM. No requirement to store SSH keys locally or on server. [github.com](https://github.com/elpy1/ssh-over-ssm)




## Kubernetes general

Kubernetes Capacity and Resource Management: It's Not What You Think It Is - DEV Community [dev.to](https://dev.to/mkdev/kubernetes-capacity-and-resource-management-its-not-what-you-think-it-is-1oik)

User and workload identities in Kubernetes [learnk8s.io](https://learnk8s.io/authentication-kubernetes)

Kubernetes Network Plugins - kubedex.com [kubedex.com](https://kubedex.com/kubernetes-network-plugins/)

etcd: getting 30% more write/s. Undertaking performance analysis on our… | by Sam Lockart | Zendesk Engineering [zendesk.engineering](https://zendesk.engineering/etcd-getting-30-more-write-s-318bcdbf7774)

Kube-fledged: Cache Container Images in Kubernetes | by Senthil Raja Chermapandian | Sep, 2021 | ITNEXT [itnext.io](https://itnext.io/kube-fledged-cache-container-images-in-kubernetes-7880a00bab91)

Kubernetes Multicluster with Kind and Cilium - Piotr's TechBlog [piotrminkowski.com](https://piotrminkowski.com/2021/10/25/kubernetes-multicluster-with-kind-and-cilium/)

How to run distributed performance tests in Kubernetes with K6 | by Javier Ramos | ITNEXT [itnext.io](https://itnext.io/how-to-run-distributed-performance-tests-in-kubernetes-with-k6-and-elasticsearch-4ff8142bc774)

Java Application Optimization on Kubernetes on the Example of a Spring Boot Microservice [medium.com](https://medium.com/faun/java-application-optimization-on-kubernetes-on-the-example-of-a-spring-boot-microservice-cf3737a2219c)

bmuschko/cka-crash-course: In-depth and hands-on practice for acing the exam. [github.com](https://github.com/bmuschko/cka-crash-course)

Introducing pvc-autoresizer - Kintone Engineering Blog [blog.kintone.io](https://blog.kintone.io/entry/pvc-autoresizer)

Kubernetes: жизнь пода / Хабр [m.habr.com](https://m.habr.com/company/flant/blog/415393/)

Почему в Kubernetes так сложно с хранилищами? / Хабр [m.habr.com](https://m.habr.com/ru/post/441222/)

За кулисами сети в Kubernetes / Хабр [m.habr.com](https://m.habr.com/company/flant/blog/420813/?utm_content=link2post)

Иллюстрированное руководство по устройству сети в Kubernetes / Блог компании Флант / Хабрахабр [habrahabr.ru](https://habrahabr.ru/company/flant/blog/346304/?utm_campaign=email_digest&utm_source=email_habrahabr&utm_medium=email_week_20180320&utm_content=link2post)

Локальные файлы при переносе приложения в Kubernetes / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/471582/?utm_content=link2post)

Масштабируем Kubernetes до 4000+ нод и 200 000 подов / Хабр [habr.com](https://habr.com/ru/company/southbridge/blog/651435/)

Из жизни с Kubernetes: Как мы выносили СУБД (и не только) из review-окружений в статическое / Блог компании Флант / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/501424/)

Как правильно сделать Kubernetes (обзор и видео доклада) / Блог компании Флант / Хабр [habr.com](https://habr.com/ru/company/flant/blog/562246/)



GitHub - kubernetes-sigs/kustomize: Customization of kubernetes YAML configurations [github.com](https://github.com/kubernetes-sigs/kustomize)

GitHub - diegolnasc/kubernetes-best-practices: A cookbook with the best practices to working with kubernetes. [github.com](https://github.com/diegolnasc/kubernetes-best-practices)

GitHub - wencaiwulue/kubevpn: KubeVPN, A vpn tunnel tools which can connect to kubernetes cluster network, you can access remote kubernetes cluster network, remote kubernetes cluster service can also access your local service [github.com](https://github.com/wencaiwulue/kubevpn)

GitHub - loft-sh/vcluster: vcluster - Create fully functional virtual Kubernetes clusters - Each vcluster runs inside a namespace of the underlying k8s cluster. It's cheaper than creating separate full-blown clusters and it offers better multi-tenancy and isolation than regular namespaces. [github.com](https://github.com/loft-sh/vcluster)

GitHub - utkuozdemir/pv-migrate: Persistent volume migration plugin for Kubernetes [github.com](https://github.com/utkuozdemir/pv-migrate)

kops/README.md at master · kubernetes/kops · GitHub [github.com](https://github.com/kubernetes/kops/blob/master/README.md)




## Kubernetes Operators and AddOns

Manage Your AWS EKS Load Balancer Like a Pro | by Meysam | Towards Data Science [towardsdatascience.com](https://towardsdatascience.com/manage-your-aws-eks-load-balancer-like-a-pro-7ca599e081ca)

clastix/capsule: Kubernetes multi-tenant Operator [github.com](https://github.com/clastix/capsule)

OpenTelemetry Operator. Tracing made easy | by Magsther | Mar, 2023 | Medium [medium.com](https://medium.com/@magstherdev/opentelemetry-operator-d3d407354cbf)

Comparing Kubernetes operators for PostgreSQL – Flant blog [blog.flant.com](https://blog.flant.com/comparing-kubernetes-operators-for-postgresql/)

Crunchy PostgreSQL Operator Documentation [access.crunchydata.com](https://access.crunchydata.com/documentation/postgres-operator/4.5.0/)

Mutating Kubernetes resources with Gatekeeper | by Lachlan Evenson | Aug, 2021 | Medium [medium.com](https://medium.com/@LachlanEvenson/mutating-kubernetes-resources-with-gatekeeper-3e5585d49ead)

Virtual Host Routing with Logical DNS Names - Aspen Mesh [aspenmesh.io](https://aspenmesh.io/virtual-host-routing-with-logical-dns-names/)

Kubernetes Ingress Controllers: How to choose the right one: Part 1 [itnext.io](https://itnext.io/kubernetes-ingress-controllers-how-to-choose-the-right-one-part-1-41d3554978d2)

Introduction to Vitess on Kubernetes for MySQL - Part I of III - Percona Database Performance Blog [www.percona.com](https://www.percona.com/blog/2020/01/13/introduction-to-vitess-on-kubernetes-for-mysql-part-i-of-iii/)

Helm Best Practices [lzone.de](https://lzone.de/blog/Helm+Best+Practices?utm_source=telegram.me&utm_medium=social&utm_campaign=helm-best-practices-ot-lars-windolfh)

Using EKS encryption provider support for defense-in-depth | Containers [aws.amazon.com](https://aws.amazon.com/blogs/containers/using-eks-encryption-provider-support-for-defense-in-depth/)

Inside The Mind Of A Problem Solver - CoreDNS 1.5.1 Fix - Curve [discover.curve.app](https://discover.curve.app/a/mind-of-a-problem-solver)

Self-Service Vault in Kubernetes [www.hashicorp.com](https://www.hashicorp.com/resources/self-service-vault-in-kubernetes)

How To Write Validating and Mutating Admission Controller Webhooks in Python for Kubernetes [medium.com](https://medium.com/analytics-vidhya/how-to-write-validating-and-mutating-admission-controller-webhooks-in-python-for-kubernetes-1e27862cb798)

Highly available Kafka cluster on Kubernetes [learnk8s.io](https://learnk8s.io/kafka-ha-kubernetes)

yannh/kubeconform: A FAST Kubernetes manifests validator, with support for Custom Resources! [github.com](https://github.com/yannh/kubeconform)

Kubernetes Storage Performance Comparison v2 (2020 Updated) | by Jakub Pavlík | volterra.io | Medium [medium.com](https://medium.com/volterra-io/kubernetes-storage-performance-comparison-v2-2020-updated-1c0b69f0dcf4)

Представляем shell-operator: создавать операторы для Kubernetes стало ещё проще / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/447442/?utm_content=link2post)

Обзор и сравнение контроллеров Ingress для Kubernetes / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/447180/?utm_content=link2post)



:: Submariner k8s VPN interconnection [submariner.io](https://submariner.io/)

k3d [k3d.io](https://k3d.io/v5.4.1/)

GitHub - jodevsa/wireguard-operator: A wireguard operator created to easily provision a VPN in a k8s cluster [github.com](https://github.com/jodevsa/wireguard-operator)

GitHub - k8spin/k8spin-operator: K8Spin multi-tenant operator - OSS [github.com](https://github.com/k8spin/k8spin-operator)

haproxy-ingress/README.md at master · jcmoraisjr/haproxy-ingress · GitHub [github.com](https://github.com/jcmoraisjr/haproxy-ingress/blob/master/examples/deployment/README.md)

GitHub - AbsaOSS/k8gb: A cloud native Kubernetes Global Balancer [github.com](https://github.com/AbsaOSS/k8gb)




## CICD and IaC

Zero Downtime Server Updates For Your Kubernetes Cluster [blog.gruntwork.io](https://blog.gruntwork.io/zero-downtime-server-updates-for-your-kubernetes-cluster-902009df5b33)

Flux from End-to-End | Flux [fluxcd.io](https://fluxcd.io/docs/flux-e2e/)

Real-World GitOps with Flux, Flagger, and Linkerd | Linkerd [linkerd.io](https://linkerd.io/2023/05/15/real-world-gitops/index.html)

Four Great Alternatives to HashiCorp’s Terraform Cloud | by Elliot Graebert | Jul, 2022 | Medium [medium.com](https://medium.com/@elliotgraebert/four-great-alternatives-to-hashicorps-terraform-cloud-6e0a3a0a5482)

Deploys at Slack - Several People Are Coding [slack.engineering](https://slack.engineering/deploys-at-slack-cd0d28c61701)

20 Terraform Best Practices to Create Clean and Reusable Code | Contino | Global Transformation Consultancy [www.contino.io](https://www.contino.io/insights/terraform-best-practices)

The “Best” Terraform CD pipeline with GitHub Actions | by Sam Gallagher | Jan, 2023 | Medium [medium.com](https://medium.com/@gallaghersam95/the-best-terraform-cd-pipeline-with-github-actions-6ecbaa5f3762)

Lessons learned from 100s of Infrastructure as Code (IaC) setups | Sören Martius [platformengineering.org](https://platformengineering.org/talks-library/infrastructure-as-code-setups)

Top 10 Best Practices for Jenkins Pipeline Plugin - Platform as a Service Magazine [www.paasmag.com](https://www.paasmag.com/2016/06/27/top-10-best-practices-for-jenkins-pipeline-plugin/)

hashicorp/tfc-workflows-github: Terraform Cloud starter workflows and github actions to automate Terraform Cloud CI/CD pipelines. [github.com](https://github.com/hashicorp/tfc-workflows-github)

Avoiding copy paste in Terraform: Two approaches for multi-environment Infra as code setups [medium.com](https://medium.com/datamindedbe/avoiding-copy-paste-in-terraform-two-approaches-for-multi-environment-infra-as-code-setups-b26b7251cb11)

Understandable Terraform projects | by Didrik Finnoy | Medium [medium.com](https://medium.com/@dfinnoy/understandable-terraform-projects-9c1cd9b4b21a)

Terraboard: 📋 A web dashboard to inspect Terraform States [github.com](https://github.com/camptocamp/terraboard)

Terraform tips & tricks: loops, if-statements, and gotchas [blog.gruntwork.io](https://blog.gruntwork.io/terraform-tips-tricks-loops-if-statements-and-gotchas-f739bbae55f9)

Scaling Jenkins – Jonathan Block – Medium [medium.com](https://medium.com/@blockjon/scaling-jenkins-bad7a4ea046f)

jenkinsci/kubernetes-plugin: Jenkins plugin to run dynamic agents in a Kubernetes/Docker environment [github.com](https://github.com/jenkinsci/kubernetes-plugin)

Keel [keel.sh](https://keel.sh/)

Automated Testing for Terraform, Docker, Packer, Kubernetes, and More [www.infoq.com](https://www.infoq.com/presentations/automated-testing-terraform-docker-packer/)

Аутентификация и чтение секретов в HashiCorp's Vault через GitLab CI / Блог компании Nixys / Хабр [habr.com](https://habr.com/ru/company/nixys/blog/512754/)

Непрерывная интеграция с помощью Drone CI, Docker и Ansible / Хабрахабр [habrahabr.ru](https://habrahabr.ru/post/324588/)

Как протестировать образ для docker за полсекунды / Блог компании Centos-admin.ru / Хабрахабр [habrahabr.ru](https://habrahabr.ru/company/centosadmin/blog/325570/)

Как сделать ваши GitLab CI пайплайны быстрее / Хабр [habr.com](https://habr.com/ru/company/gitlab/blog/646579/)

Лучшие практики для деплоя высокодоступных приложений в Kubernetes. Часть 1 / Флант / Хабр [m.habr.com](https://m.habr.com/ru/company/flant/blog/545204/)

Настройка окружения для сборки и тестирования приложения в закрытом периметре / Блог компании EPAM / Хабрахабр [habrahabr.ru](https://habrahabr.ru/company/epam_systems/blog/176719/)



dlvhdr/gh-dash: A beautiful CLI dashboard for GitHub 🚀 [github.com](https://github.com/dlvhdr/gh-dash)

utils/terraform/aws-oidc-ci at main · marco-lancini/utils [github.com](https://github.com/marco-lancini/utils/tree/main/terraform/aws-oidc-ci)

distroless-springboot [github.com](https://github.com/pragmasoft-ua/spring-boot-base-docker-image/blob/master/Dockerfile)

GitHub - uber/kraken: P2P Docker registry capable of distributing TBs of data in seconds [github.com](https://github.com/uber/kraken)

go-containerregistry/recipes.md at main · google/go-containerregistry · GitHub [github.com](https://github.com/google/go-containerregistry/blob/main/cmd/crane/recipes.md)

GitHub - pipe-cd/pipe: Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications [github.com](https://github.com/pipe-cd/pipe)

GitHub - stefanprodan/gitops-istio: GitOps Progressive Delivery demo with Istio, Flux, Helm Operator and Flagger [github.com](https://github.com/stefanprodan/gitops-istio)

Guide | Keel [keel.sh](https://keel.sh/docs/#deploying-with-helm)

GitHub - valentindeaconu/terralist: A private Terraform registry [github.com](https://github.com/valentindeaconu/terralist)

GitHub - dineshba/tf-summarize: A command-line utility to print the summary of the terraform plan [github.com](https://github.com/dineshba/tf-summarize)

GitHub - awslabs/amazon-ecr-credential-helper: Automatically gets credentials for Amazon ECR on docker push/docker pull [github.com](https://github.com/awslabs/amazon-ecr-credential-helper)

GitHub - vmware-tanzu/buildkit-cli-for-kubectl: BuildKit CLI for kubectl is a tool for building container images with your Kubernetes cluster [github.com](https://github.com/vmware-tanzu/buildkit-cli-for-kubectl)

GitHub - docker-slim/docker-slim: DockerSlim (docker-slim): Don't change anything in your Docker container image and minify it by up to 30x (and for compiled languages even more) making it secure too! (free and open source) [github.com](https://github.com/docker-slim/docker-slim)




## Observability

Deploying a Modern Monitoring Stack (Part 1) | by Caoimhe Harvey | Dev Genius [blog.devgenius.io](https://blog.devgenius.io/deploying-a-modern-monitoring-stack-part-1-5eb8ada105ba)

How to Build an End to End Open Source Observability Solution on Kubernetes | by Eden Federman | Aug, 2022 | Medium [medium.com](https://medium.com/@edeNFed/how-to-build-an-end-to-end-open-source-observability-solution-on-kubernetes-c8725c016dd5)

Multi-Cluster Monitoring with Thanos [particule.io](https://particule.io/en/blog/thanos-monitoring/)

Build an observability solution using managed AWS services and the OpenTelemetry standard | AWS Cloud Operations & Migrations Blog [aws.amazon.com](https://aws.amazon.com/blogs/mt/build-an-observability-solution-using-managed-aws-services-and-the-opentelemetry-standard/)

Using OpenTelemetry auto-instrumentation/agents in Kubernetes | by Pavol Loffay | OpenTelemetry | Medium [medium.com](https://medium.com/opentelemetry/using-opentelemetry-auto-instrumentation-agents-in-kubernetes-869ec0f42377)

What is OpenTelemetry? The Definitive Guide | Aspecto [www.aspecto.io](https://www.aspecto.io/blog/what-is-opentelemetry-the-infinitive-guide/?utm_source=jaeger-medium&utm_medium=post&utm_campaign=jaeger-tracing-the-ultimate-guide)

SDK Registry | OpenTelemetry [opentelemetry.io](https://opentelemetry.io/registry/)

17 DevOps Metrics To Measure Success | by Semaphore | Medium [semaphoreci.medium.com](https://semaphoreci.medium.com/17-devops-metrics-to-measure-success-cca66a9e79c)

6 Metrics to Watch for on Your K8s Cluster | by Erez Rabih | May, 2022 | Medium [erezrabih.medium.com](https://erezrabih.medium.com/6-metrics-to-watch-for-on-your-k8s-cluster-76d58f08397f)

USE vs RED vs The Four Golden Signals | by Magsther | FAUN Publication [medium.com](https://medium.com/faun/use-vs-red-vs-the-four-golden-signals-50655e93fad7)

Top key metrics for monitoring MySQL – Sysdig [sysdig.com](https://sysdig.com/blog/mysql-monitoring/)

Elasticsearch Performance Tuning Practice at eBay [www.ebayinc.com](https://www.ebayinc.com/stories/blogs/tech/elasticsearch-performance-tuning-practice-at-ebay/)

Parsing SSH Logs with Grafana Loki [voidquark.com](https://voidquark.com/parsing-ssh-logs-with-grafana-loki/)

BotKube :: Messaging bot for monitoring and debugging Kubernetes clusters [www.botkube.io](https://www.botkube.io/)

Code972 :: Why you shouldn't use AWS Elasticsearch Service [code972.com](https://code972.com/blog/2017/12/111-why-you-shouldnt-use-aws-elasticsearch-service)

PromQL for Humans [timber.io](https://timber.io/blog/promql-for-humans/#offset)

Using Environment Variables for Configuration, Provisioning, and Dashboards in Grafana | by Mikhail Volkov | Feb, 2022 | Volkov Labs [volkovlabs.com](https://volkovlabs.com/using-environment-variables-for-configuration-provisioning-and-dashboards-in-grafana-279661733416)

Horizontally Scaling Prometheus at Wish - Wish Engineering And Data Science - Medium [medium.com](https://medium.com/wish-engineering/horizontally-scaling-prometheus-at-wish-ea4b694318dd)

Monitoring Jenkins with Grafana and Prometheus – Mohamed Saeed – Medium [medium.com](https://medium.com/@eng.mohamed.m.saeed/monitoring-jenkins-with-grafana-and-prometheus-a7e037cbb376)

Введение в ELK: собираем, фильтруем и анализируем большие данные | статьи о программировании mkdev [mkdev.me](https://mkdev.me/posts/vvedenie-v-elk-sobiraem-filtruem-i-analiziruem-bolshie-dannye)

Как мы Elasticsearch в порядок приводили: разделение данных, очистка, бэкапы / Блог компании Флант / Хабр [habr.com](https://habr.com/ru/company/flant/blog/490026/)



GitHub - dotdc/grafana-dashboards-kubernetes: A set of modern Grafana dashboards for Kubernetes. [github.com](https://github.com/dotdc/grafana-dashboards-kubernetes)

query-exporter/query_exporter at master · albertodonato/query-exporter · GitHub [github.com](https://github.com/albertodonato/query-exporter/tree/master/query_exporter)

GitHub - prymitive/karma: Alert dashboard for Prometheus Alertmanager [github.com](https://github.com/prymitive/karma)

GitHub - prabhatsharma/zinc: Zinc Search engine. A lightweight alternative to elasticsearch that requires minimal resources, written in Go. [github.com](https://github.com/prabhatsharma/zinc)

GitHub - TwinProduction/gatus: ⛑ Gatus - Automated service health dashboard [github.com](https://github.com/TwinProduction/gatus)

GitHub - kinvolk/inspektor-gadget: Collection of gadgets for debugging and introspecting Kubernetes applications using BPF [github.com](https://github.com/kinvolk/inspektor-gadget)

GitHub - idealista/prom2teams: prom2teams is an HTTP server built with Python that receives alert notifications from a previously configured Prometheus Alertmanager instance and forwards it to Microsoft Teams using defined connectors [github.com](https://github.com/idealista/prom2teams)

GitHub - SigNoz/signoz: SigNoz is an open-source APM. It helps developers monitor their applications & troubleshoot problems, an open-source alternative to DataDog, NewRelic, etc. 🔥 🖥. 👉 Open source Application Performance Monitoring (APM) & Observability tool [github.com](https://github.com/signoz/signoz)




## Security

KubeSecOps Pipeline(Container security) in a cloudnative ecosystem | by Vaibhav Chopra | Sep, 2020 | Medium [medium.com](https://medium.com/@vaib16dec/kubesecops-pipeline-container-security-in-a-cloudnative-ecosystem-e59bf19a713d)

A Secure Cloud [asecure.cloud](https://asecure.cloud/)

OWASP Top 10 CI/CD Security Risks | OWASP Foundation [owasp.org](https://owasp.org/www-project-top-10-ci-cd-security-risks/?utm_source=telegram&utm_medium=deflope&utm_campaign=-1001033513075&utm_term=2022_12_19_10_50&utm_content=292896753)

Top 20 Dockerfile best practices for security | Sysdig [sysdig.com](https://sysdig.com/blog/dockerfile-best-practices/)

5 best practices to get to production readiness with Hashicorp Vault in Kubernetes - Expel [expel.io](https://expel.io/blog/production-readiness-hashicorp-vault-kubernetes/)

DevSecOps — When “infrastructure as code” meets “security as code” | by Ravi Rajamiyer | FAUN Publication [faun.pub](https://faun.pub/devsecops-when-infrastructure-as-code-meets-security-as-code-2a218ce2381d)

Identity and Access Management - EKS Best Practices Guide for Security [aws.github.io](https://aws.github.io/aws-eks-best-practices/iam/)

aquasecurity/kube-bench: Checks whether Kubernetes is deployed according to security best practices as defined in the CIS Kubernetes Benchmark [github.com](https://github.com/aquasecurity/kube-bench)

armosec/kubescape: kubescape is the first tool for testing if Kubernetes is deployed securely as defined in Kubernetes Hardening Guidance by to NSA and CISA (https://www.nsa.gov/News-Features/Feature-Stories/Article-View/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/) [github.com](https://github.com/armosec/kubescape)

Стандарты безопасности в Kubernetes (обзор и видео доклада) / Хабр [habr.com](https://habr.com/ru/companies/vk/articles/730158/)



GitHub - deepfence/SecretScanner: Find secrets and passwords in container images and file systems [github.com](https://github.com/deepfence/SecretScanner)

GitHub - fivexl/aws-ecr-client-golang: AWS ECR client to automated push to ECR and handling of vulnerability [github.com](https://github.com/fivexl/aws-ecr-client-golang)

GitHub - toniblyx/my-arsenal-of-aws-security-tools: List of open source tools for AWS security: defensive, offensive, auditing, DFIR, etc. [github.com](https://github.com/toniblyx/my-arsenal-of-aws-security-tools)

vchinnipilli/kubestriker: A Blazing fast Security Auditing tool for Kubernetes [github.com](https://github.com/vchinnipilli/kubestriker)




## SRE

A Step-by-Step Guide to Calculate SLAs, SLIs, and SLOs for Your IT Services | by Abhishek Gupta | Mar, 2023 | AceTheCloud [blog.acethecloud.com](https://blog.acethecloud.com/a-step-by-step-guide-to-calculating-slas-slis-and-slos-for-your-it-services-6f0a07b67bb5)

Availability window, SRE [landing.google.com](https://landing.google.com/sre/book/chapters/availability-table.html#appendix_table-of-nines)

SREcon: Performance Checklists for SREs 2016 [www.brendangregg.com](https://www.brendangregg.com/blog/2016-05-04/srecon2016-perf-checklists-for-sres.html)

Monitoring SRE's Golden Signals [www.infoq.com](https://www.infoq.com/articles/monitoring-SRE-golden-signals/)




## Serverless

Serverless Framework vs SAM vs AWS CDK [tastefulelk.hashnode.dev](https://tastefulelk.hashnode.dev/serverless-framework-vs-sam-vs-aws-cdk)

Serverless patterns | Serverless Land [serverlessland.com](https://serverlessland.com/patterns)

Introducing AWS SAM Pipelines: Automatically generate deployment pipelines for serverless applications | AWS Compute Blog [aws.amazon.com](https://aws.amazon.com/blogs/compute/introducing-aws-sam-pipelines-automatically-generate-deployment-pipelines-for-serverless-applications/)

lambci/lambci: A continuous integration system built on AWS Lambda [github.com](https://github.com/lambci/lambci)

sam deploy permissions? · Issue #420 · aws/aws-sam-cli [github.com](https://github.com/aws/aws-sam-cli/issues/420)

dherault/serverless-offline: Emulate AWS λ and API Gateway locally when developing your Serverless project [github.com](https://github.com/dherault/serverless-offline)



## Software Development

TheAlgorithms/Python: All Algorithms implemented in Python [github.com](https://github.com/TheAlgorithms/Python)

Build simple TCP Server with Python built-in SocketServer module | Gatsby: Software Engineer [software-engineer.gatsbylee.com](http://software-engineer.gatsbylee.com/create-simple-tcp-server-with-python-built-in-socketserver-module/)

GitHub - benkehoe/aws-assume-role-lib: Assumed role session chaining (with credential refreshing) for boto3 [github.com](https://github.com/benkehoe/aws-assume-role-lib)

Interprocess communication in Python - Stack Overflow [stackoverflow.com](https://stackoverflow.com/questions/6920858/interprocess-communication-in-python)

Signals and Slots (registering callbacks) — Pizco 0.1 documentation [pizco.readthedocs.io](https://pizco.readthedocs.io/en/latest/signals.html)

A guide to Python's function decorators [www.thecodeship.com](https://www.thecodeship.com/patterns/guide-to-python-function-decorators/)

Свой асинхронный tcp-сервер за 15 минут с подробным разбором / Блог компании Альфа-Банк / Хабр [habr.com](https://habr.com/company/alfa/blog/354728/)

Учебник – Нейронные сети [neuralnet.info](https://neuralnet.info/book/)

Наглядно о том, как работает NumPy / Блог компании SkillFactory / Хабр [habr.com](https://habr.com/ru/company/skillfactory/blog/564240/)

An A-Z of useful Python tricks – freeCodeCamp [medium.freecodecamp.org](https://medium.freecodecamp.org/an-a-z-of-useful-python-tricks-b467524ee747)

How to completely traverse a complex dictionary of unknown depth? - Stack Overflow [stackoverflow.com](https://stackoverflow.com/questions/12507206/how-to-completely-traverse-a-complex-dictionary-of-unknown-depth)




## Unsorted

Building Self-driving Kafka clusters using open source components - Slack Engineering [slack.engineering](https://slack.engineering/building-self-driving-kafka-clusters-using-open-source-components/)

PostgREST Documentation — PostgREST 7.0.1 documentation [postgrest.org](https://postgrest.org/en/stable/)

How to measure Linux Performance Avoiding Most Typical Mistakes: CPU [ma.ttias.be](https://ma.ttias.be/how-to-measure-linux-performance-avoiding-most-typical-mistakes-cpu/)

PostgreSQL Replication with Docker  [medium.com](https://medium.com/swlh/postgresql-replication-with-docker-c6a904becf77)

Minimal Oracle installation (and Docker image) - Franck Pachot - Medium [medium.com](https://medium.com/@FranckPachot/minimal-oracle-installation-and-docker-image-ed47447e62a0)


Кластер высокой доступности на postgresql 9.6 + repmgr + pgbouncer + haproxy + keepalived + контроль через telegram / Блог компании ESOFT / Хабрахабр [habrahabr.ru](https://habrahabr.ru/company/etagi/blog/314000/)


Deploying artifacts to Maven using Gradle – .debug – Medium [medium.com](https://medium.com/dot-debug/deploying-artifacts-to-maven-using-gradle-b669acc1b6f8)

Don't Put Fat Jars in Docker Images [phauer.com](https://phauer.com/2019/no-fat-jar-in-docker-image/)

Оптимизация настроек Redis . Хайлоад [ruhighload.com](https://ruhighload.com/post/%D0%9E%D0%BF%D1%82%D0%B8%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F+%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BA+Redis)

Nginx + Lua, гибкая балансировка нагрузки с сохранением сессии / Хабрахабр [habrahabr.ru](https://habrahabr.ru/post/326486/)

Оптимальная настройка Nginx . Хайлоад [ruhighload.com](https://ruhighload.com/index.php/2009/04/24/%d0%bd%d0%b0%d1%81%d1%82%d1%80%d0%be%d0%b9%d0%ba%d0%b0-nginx/)

Кэширование с Nginx . Хайлоад [ruhighload.com](https://ruhighload.com/post/%D0%9A%D1%8D%D1%88%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5+%D1%81+Nginx)

Магия SSH / Хабрахабр [habrahabr.ru](https://habrahabr.ru/post/331348/)

Как быстро удалить множество строк из большой базы в MySQL / Хабрахабр [habrahabr.ru](https://habrahabr.ru/post/332182/)

Тюнинг сетевого стека Linux для ленивых / Хабрахабр [habrahabr.ru](https://habrahabr.ru/post/331720/)

Пособие по Ansible / Хабрахабр [habrahabr.ru](https://habrahabr.ru/post/305400/)

Докеризация высокодоступного Postgres кластера / Хабрахабр [habrahabr.ru](https://habrahabr.ru/post/334484/)

How To Configure Nginx with SSL as a Reverse Proxy for Jenkins | DigitalOcean [www.digitalocean.com](https://www.digitalocean.com/community/tutorials/how-to-configure-nginx-with-ssl-as-a-reverse-proxy-for-jenkins)

gort/README.md at master · idestis/gort · GitHub [github.com](https://github.com/idestis/gort/blob/master/README.md)

GitHub - Yelp/dumb-init: A minimal init system for Linux containers [github.com](https://github.com/yelp/dumb-init)

Maven Publish Plugin [docs.gradle.org](https://docs.gradle.org/current/userguide/publishing_maven.html)

Caddy - The HTTP/2 Web Server with Automatic HTTPS [caddyserver.com](https://caddyserver.com/)

bpftrace (DTrace 2.0) for Linux 2018 [www.brendangregg.com](http://www.brendangregg.com/blog/2018-10-08/dtrace-for-linux-2018.html)

Экстремальная настройка производительности HTTP: 1,2M API RPS на инстансе EC2 с 4 виртуальными процессорами (vCPU) / Хабр [habr.com](https://habr.com/ru/company/flant/blog/651867/)



GitHub - GoogleContainerTools/distroless: 🥑 Language focused docker images, minus the operating system. [github.com](https://github.com/GoogleContainerTools/distroless)

batchcorp/plumber: A swiss army knife CLI tool for interacting with Kafka, RabbitMQ and other messaging systems. [github.com](https://github.com/batchcorp/plumber)

GitHub - tomav/docker-mailserver: A fullstack but simple mailserver (smtp, imap, antispam, antivirus, ssl...) using Docker. [github.com](https://github.com/tomav/docker-mailserver)

GitHub - flant/ovpn-admin: Simple web UI to manage OpenVPN users. [github.com](https://github.com/flant/ovpn-admin)

GitHub - fabianlindfors/reshape: An easy-to-use, zero-downtime schema migration tool for Postgres [github.com](https://github.com/fabianlindfors/reshape)
GitHub - genereese/togo: A script to create RPMs in less than five minutes from start to finish. [github.com](https://github.com/genereese/togo)

GitHub - xo/usql: Universal command-line interface for SQL databases [github.com](https://github.com/xo/usql)

GitHub - readysettech/readyset: ReadySet is a lightweight SQL caching engine written in Rust that helps developers enhance the performance and scalability of existing applications. [github.com](https://github.com/readysettech/readyset)

GitHub - kellyjonbrazil/jc: CLI tool and python library that converts the output of popular command-line tools, file-types, and common strings to JSON, YAML, or Dictionaries. This allows piping of output to tools like jq and simplifying automation scripts. [github.com](https://github.com/kellyjonbrazil/jc)
