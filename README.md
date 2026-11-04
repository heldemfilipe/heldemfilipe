<h1 align="center">Heldem Filipe</h1>
<p align="center">
  DevOps / Cloud / Platform Engineer · 5 anos de experiência<br>
  Infraestrutura como código, GitOps, pipelines e observabilidade na AWS · Java e Spring Boot como segunda frente
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/heldem-filipe">LinkedIn</a> ·
  <a href="mailto:heldemfilipe@gmail.com">E-mail</a> ·
  Rio Claro, SP · Aberto a oportunidades (remoto ou híbrido)
</p>

---

## Certificações

- **AWS Certified Solutions Architect – Associate** (SAA-C03), ago/2026
- **AWS Certified Developer – Associate** (DVA-C02), out/2026
- **AWS Certified Cloud Practitioner** (CLF-C02), nov/2026

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,terraform,kubernetes,docker,prometheus,grafana,gitlab&perline=7" alt="Stack" />
  <br>
  <img src="https://skillicons.dev/icons?i=githubactions,python,java,spring,mongodb,kafka&perline=6" alt="Stack" /><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/argocd/argocd-original.svg" alt="Argo CD" width="48" height="48" />
</p>

| Área | O que uso |
|---|---|
| Cloud | AWS (ECS Fargate, EKS, IAM) |
| IaC | Terraform (módulos, testes com `terraform test`, versionamento por tag) |
| CI/CD e GitOps | GitLab CI, GitHub Actions (OIDC, plan/apply com aprovação), Argo CD |
| Segurança e qualidade | Trivy, tflint, gitleaks, OPA/conftest e Kyverno (policy as code) |
| Containers | Docker, Kubernetes (kind, EKS), NetworkPolicy, PDB e HPA |
| Observabilidade | Prometheus, Alertmanager e Grafana (kube-prometheus-stack) |
| Linguagens | Python, Java (Spring Boot) |

---

## Projetos em destaque

| Projeto | O que prova | Stack |
|---|---|---|
| [eks-gitops-platform](https://github.com/heldemfilipe/eks-gitops-platform) + [eks-gitops-config](https://github.com/heldemfilipe/eks-gitops-config) | Plataforma Kubernetes em camadas (rede, EKS, bootstrap) operada por GitOps: entrega por PR com o Argo CD sincronizando em ~82 s, observabilidade com alertas, guardrails (Kyverno, NetworkPolicy, PDB, HPA) e cinco experimentos de falha medidos, mais custo estimado e runbook de upgrade | Terraform, Argo CD, Kubernetes, Kyverno, Prometheus |
| [terraform-aws-foundation](https://github.com/heldemfilipe/terraform-aws-foundation) | Fundação de IaC: módulos testados e versionados por tag, pipeline plan/apply por OIDC com aprovação manual, políticas que bloqueiam o PR e detecção de drift sob demanda, com runbook | Terraform, GitHub Actions, OPA |
| [orders-api](https://github.com/heldemfilipe/orders-api) | API REST com Kafka e MongoDB, circuit breaker, testes de integração com Testcontainers, Docker, CI e infraestrutura em Terraform | Java, Spring Boot, Kafka, MongoDB |
| [radar-tech](https://github.com/heldemfilipe/radar-tech) | Pipeline 100% automatizado (RSS → Gemini → TTS → Telegram) com custo zero | Python, GitHub Actions |

> `terraform-aws-foundation` e `eks-gitops-platform` são projetos de estudo: validados com testes, `plan` offline e políticas, **nunca aplicados na AWS**. No segundo, o cluster que rodou de verdade é um `kind` local. Os READMEs mostram o que foi executado e o que não foi.

---

## Experiência

- **GFT Technologies** (ago/2025 – out/2026): Analista DevOps Pleno, infraestrutura cloud para o setor financeiro
- **Casa do Construtor** (jun/2021 – jul/2025): de estagiário a Analista DevOps Pleno, responsável pela área de DevOps

---

## Estudando agora

- AWS Certifications
- Mensageria e NoSQL em Java (Kafka, MongoDB)
- Inglês técnico
