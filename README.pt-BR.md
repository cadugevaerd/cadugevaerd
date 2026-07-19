# Carlos Eduardo Gevaerd Araujo

> **Especialista em DevOps e Engenharia de IA**  
> [English](README.md)

Construo sistemas de IA confiáveis — de recuperação com grounding e fluxos de agentes até runtime em cloud, avaliação e automação de entrega.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carlos-gevaerd-araujo)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cadugevaerd)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cadu.gevaerd@gmail.com)

---

## Foco

- **Sistemas de IA com grounding**, orquestração determinística, recuperação e comportamento seguro de fallback.
- **Avaliação de LLMs e quality gates** para transformar a entrega de IA em uma disciplina de engenharia baseada em evidências.
- **Plataformas de IA cloud-native** com AWS, containers, Kubernetes, infraestrutura como código e CI/CD.

## Projetos em Destaque de Engenharia de IA

### 1. [RAG Híbrido na AWS — Bedrock AgentCore](https://github.com/cadugevaerd/hybrid-rag-bedrock-agentcore)

Lab de RAG híbrido e determinístico implantado no **AWS Bedrock AgentCore Runtime**.

- **Recuperação:** Amazon Bedrock Managed Knowledge Base com busca híbrida.
- **Orquestração:** fluxo determinístico de recuperação para resposta com LangGraph; geração via OpenRouter.
- **Runtime:** aplicação implantável no AgentCore, com credenciais fora do repositório público.
- **Qualidade:** evidências de avaliação versionadas cobrem correspondência exata, recuperação semântica, recusa com grounding fora do corpus e freshness.

`Bedrock Managed Knowledge Base → LangGraph → OpenRouter → Bedrock AgentCore Runtime`

### 2. [LLM as a Judge](https://github.com/cadugevaerd/llm-as-a-judge-api)

Sistema para avaliar e comparar respostas de LLMs.

- Avaliação agnóstica de provedor via OpenRouter.
- Processamento em lote e estatísticas de performance.
- Entrega orientada a produção com FastAPI, Docker, Kubernetes e Helm.

### 3. [Verify · Review · Ship — Extensão para GitHub Spec Kit](https://github.com/cadugevaerd/spec-kit-verify-review-ship)

Extensão comunitária para o GitHub Spec Kit que adiciona quality gates pós-build ao fluxo de entrega guiado por especificação.

- **Verify:** artefatos, rastreabilidade de tarefas, diffs e gates do projeto.
- **Review:** correção, legibilidade, arquitetura, segurança e performance.
- **Ship:** decisão de prontidão GO / NO-GO com checklist e plano de rollback.

### 4. [Ecossistema de Agent Skills](https://github.com/cadugevaerd/claude-skills)

Agent Skills reutilizáveis e instaláveis seletivamente para fluxos de trabalho no Claude Code e Codex, voltadas a transformar práticas repetíveis de engenharia em ferramentas portáteis.

## Engenharia de Plataforma Selecionada

### [Automação de Upgrade K3s](https://github.com/cadugevaerd/k3s-configs)

Automação de upgrades sem downtime para clusters Kubernetes, com validações, backup e mecanismos de rollback.

### [Tailscale Userspace Proxy](https://github.com/cadugevaerd/tailscale-userspace-proxy)

Proxy SOCKS5/HTTP para ambientes restritos que executa o Tailscale no modo userspace via Docker, sem exigir `/dev/net/tun`.

## Foco Tecnológico

`Python` · `LangGraph` · `LangChain` · `OpenRouter` · `AWS Bedrock` · `AgentCore` · `LLM Evals` · `Docker` · `Kubernetes` · `Terraform` · `GitHub Actions` · `Tailscale`

## Formação e Credenciais

- Pós-graduação em **Engenharia DevOps e Continuous Software Engineering** — PUC Minas (2024–2025)
- Tecnólogo em **Redes de Computadores** — Estácio (2018–2020)
- **AWS Certified Cloud Practitioner**
- **ITIL Foundation**

---

## Vamos construir sistemas de IA confiáveis

Estou aberto para conversar sobre engenharia de IA, plataformas cloud, automação e qualidade de entrega.

[LinkedIn](https://www.linkedin.com/in/carlos-gevaerd-araujo/) · [Email](mailto:cadu.gevaerd@gmail.com)
