# Guia de Uso dos Agentes

> Como usar os agentes deste repositorio, mesmo sem saber programar.

---

## O que sao esses agentes?

Cada agente e um arquivo `.md` com instrucoes detalhadas que transformam uma IA (Claude, ChatGPT, Gemini) em um especialista. Nao e um programa — e um texto que voce cola no chat.

---

## Como usar

### Pelo celular (sem programar)

1. Acesse o repositorio pelo navegador
2. Abra a pasta do agente que voce quer (ex: `marketing/`)
3. Toque no arquivo `.md` do agente
4. Copie todo o conteudo
5. Abra o app do **Claude**, **ChatGPT** ou **Gemini**
6. Cole o texto como primeira mensagem
7. Envie seu pedido normalmente

### Pelo computador com Claude Code

```bash
cp -r agency-agents/* ~/.claude/agents/
```

### Com outras ferramentas (Cursor, Aider, Windsurf)

```bash
./scripts/convert.sh
./scripts/install.sh
```

---

## Catalogo completo de agentes

### Marketing (11 agentes)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| Content Creator | `marketing/marketing-content-creator.md` | Estrategista de conteudo para campanhas multiplataforma, calendarios editoriais e engajamento |
| Growth Hacker | `marketing/marketing-growth-hacker.md` | Especialista em crescimento rapido com experimentos orientados por dados e mecanicas virais |
| Social Media Strategist | `marketing/marketing-social-media-strategist.md` | Estrategista de redes sociais para LinkedIn, Twitter e plataformas profissionais |
| Instagram Curator | `marketing/marketing-instagram-curator.md` | Especialista em Instagram: storytelling visual, comunidade e conteudo multiformato |
| TikTok Strategist | `marketing/marketing-tiktok-strategist.md` | Especialista em TikTok: conteudo viral, otimizacao de algoritmo e comunidade |
| Twitter Engager | `marketing/marketing-twitter-engager.md` | Especialista em Twitter: engajamento em tempo real e lideranca de pensamento |
| Reddit Community Builder | `marketing/marketing-reddit-community-builder.md` | Especialista em Reddit: engajamento autentico e conteudo de valor |
| App Store Optimizer | `marketing/marketing-app-store-optimizer.md` | Especialista em ASO (App Store Optimization) e otimizacao de conversao |
| Xiaohongshu Specialist | `marketing/marketing-xiaohongshu-specialist.md` | Especialista em Xiaohongshu: conteudo lifestyle e estrategias de tendencia |
| Zhihu Strategist | `marketing/marketing-zhihu-strategist.md` | Especialista em Zhihu: lideranca de pensamento e engajamento baseado em conhecimento |
| WeChat Account Manager | `marketing/marketing-wechat-official-account.md` | Estrategista de WeChat OA: marketing de conteudo e engajamento de assinantes |

### Design (8 agentes)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| UI Designer | `design/design-ui-designer.md` | Designer de interfaces, sistemas de design e bibliotecas de componentes |
| UX Researcher | `design/design-ux-researcher.md` | Pesquisador de experiencia do usuario, testes de usabilidade e insights baseados em dados |
| UX Architect | `design/design-ux-architect.md` | Arquiteto de UX tecnico com sistemas CSS e orientacao de implementacao |
| Brand Guardian | `design/design-brand-guardian.md` | Estrategista de marca: identidade, consistencia e posicionamento |
| Visual Storyteller | `design/design-visual-storyteller.md` | Especialista em comunicacao visual e narrativas de marca |
| Image Prompt Engineer | `design/design-image-prompt-engineer.md` | Engenheiro de prompts para geracao de imagens e fotografia profissional |
| Whimsy Injector | `design/design-whimsy-injector.md` | Especialista criativo em adicionar personalidade e elementos ludicos a marcas |
| Inclusive Visuals Specialist | `design/design-inclusive-visuals-specialist.md` | Especialista em representatividade e combate a vieses em imagens geradas por IA |

### Engenharia (11 agentes)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| Frontend Developer | `engineering/engineering-frontend-developer.md` | Desenvolvedor frontend: React, Vue, Angular e otimizacao de performance |
| Backend Architect | `engineering/engineering-backend-architect.md` | Arquiteto backend: design de sistemas escalaveis, bancos de dados e cloud |
| Senior Developer | `engineering/engineering-senior-developer.md` | Especialista em Laravel/Livewire/FluxUI, CSS avancado e Three.js |
| AI Engineer | `engineering/engineering-ai-engineer.md` | Engenheiro de IA/ML: desenvolvimento, deploy e integracao de modelos |
| Data Engineer | `engineering/engineering-data-engineer.md` | Engenheiro de dados: pipelines, lakehouse e infraestrutura escalavel |
| DevOps Automator | `engineering/engineering-devops-automator.md` | Engenheiro DevOps: automacao de infraestrutura, CI/CD e cloud |
| Security Engineer | `engineering/engineering-security-engineer.md` | Engenheiro de seguranca: modelagem de ameacas e arquitetura segura |
| Mobile App Builder | `engineering/engineering-mobile-app-builder.md` | Desenvolvedor mobile: iOS, Android nativo e multiplataforma |
| Rapid Prototyper | `engineering/engineering-rapid-prototyper.md` | Especialista em prototipagem rapida e criacao de MVPs |
| Technical Writer | `engineering/engineering-technical-writer.md` | Escritor tecnico: documentacao, referencias de API e tutoriais |
| Autonomous Optimization Architect | `engineering/engineering-autonomous-optimization-architect.md` | Governador de sistemas que testa APIs para performance com guardrails financeiros |

### Produto (4 agentes)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| Sprint Prioritizer | `product/product-sprint-prioritizer.md` | Gerente de produto: planejamento de sprints e priorizacao de features |
| Trend Researcher | `product/product-trend-researcher.md` | Analista de inteligencia de mercado e tendencias emergentes |
| Feedback Synthesizer | `product/product-feedback-synthesizer.md` | Especialista em coletar e analisar feedback de usuarios |
| Behavioral Nudge Engine | `product/product-behavioral-nudge-engine.md` | Especialista em psicologia comportamental para maximizar motivacao do usuario |

### Testes e Qualidade (8 agentes)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| Reality Checker | `testing/testing-reality-checker.md` | Especialista senior em integracao que exige evidencias antes de certificar producao |
| Evidence Collector | `testing/testing-evidence-collector.md` | QA obsessivo por screenshots que exige prova visual de tudo |
| API Tester | `testing/testing-api-tester.md` | Especialista em testes de API: validacao, performance e qualidade |
| Performance Benchmarker | `testing/testing-performance-benchmarker.md` | Especialista em testes de performance e melhoria de sistemas |
| Accessibility Auditor | `testing/testing-accessibility-auditor.md` | Especialista em acessibilidade e padroes WCAG |
| Test Results Analyzer | `testing/testing-test-results-analyzer.md` | Especialista em analise de resultados de testes e metricas de qualidade |
| Workflow Optimizer | `testing/testing-workflow-optimizer.md` | Especialista em melhoria de processos e automacao de workflows |
| Tool Evaluator | `testing/testing-tool-evaluator.md` | Especialista em avaliacao e recomendacao de ferramentas |

### Suporte e Operacoes (6 agentes)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| Support Responder | `support/support-support-responder.md` | Especialista em atendimento ao cliente e resolucao de problemas |
| Analytics Reporter | `support/support-analytics-reporter.md` | Analista de dados: transforma dados brutos em insights e dashboards |
| Finance Tracker | `support/support-finance-tracker.md` | Analista financeiro: planejamento e gestao de orcamento |
| Legal Compliance Checker | `support/support-legal-compliance-checker.md` | Especialista em compliance legal e regulatorio |
| Executive Summary Generator | `support/support-executive-summary-generator.md` | Especialista em transformar informacoes complexas em resumos executivos |
| Infrastructure Maintainer | `support/support-infrastructure-maintainer.md` | Especialista em confiabilidade de sistemas e otimizacao de infraestrutura |

### Estrategia (1 agente)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| NEXUS | `strategy/nexus-strategy.md` | Playbook operacional para orquestracao e coordenacao de multiplos agentes |

### Gestao de Projetos (5 agentes)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| Senior Project Manager | `project-management/project-manager-senior.md` | Converte especificacoes em tarefas com foco em escopo realista |
| Project Shepherd | `project-management/project-management-project-shepherd.md` | Gerente de projetos: coordenacao cross-funcional e alinhamento de stakeholders |
| Studio Producer | `project-management/project-management-studio-producer.md` | Lider estrategico em orquestracao criativa e tecnica |
| Studio Operations | `project-management/project-management-studio-operations.md` | Gerente de operacoes focado em eficiencia e otimizacao de processos |
| Experiment Tracker | `project-management/project-management-experiment-tracker.md` | Gerente de experimentos: design, execucao e decisoes baseadas em dados |

### Computacao Espacial (6 agentes)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| XR Interface Architect | `spatial-computing/xr-interface-architect.md` | Designer de interacao espacial para ambientes imersivos AR/VR/XR |
| XR Immersive Developer | `spatial-computing/xr-immersive-developer.md` | Desenvolvedor WebXR para AR/VR/XR no navegador |
| visionOS Spatial Engineer | `spatial-computing/visionos-spatial-engineer.md` | Engenheiro visionOS: SwiftUI volumetrico e Liquid Glass |
| macOS Spatial/Metal Engineer | `spatial-computing/macos-spatial-metal-engineer.md` | Especialista em Swift e Metal para renderizacao 3D de alta performance |
| XR Cockpit Specialist | `spatial-computing/xr-cockpit-interaction-specialist.md` | Especialista em sistemas de controle em cockpit para ambientes XR |
| Terminal Integration Specialist | `spatial-computing/terminal-integration-specialist.md` | Especialista em emulacao de terminal e renderizacao de texto em Swift |

### Agentes Especializados (9 agentes)

| Agente | Arquivo | O que faz |
|--------|---------|-----------|
| Developer Advocate | `specialized/specialized-developer-advocate.md` | Advocate: comunidades de desenvolvedores, conteudo tecnico e DX |
| Cultural Intelligence Strategist | `specialized/specialized-cultural-intelligence-strategist.md` | Especialista em inteligencia cultural e inclusao em software |
| Agents Orchestrator | `specialized/agents-orchestrator.md` | Gerenciador de pipeline autonomo: do spec a producao |
| Agentic Identity & Trust Architect | `specialized/agentic-identity-trust.md` | Arquiteto de identidade e confianca para agentes de IA autonomos |
| LSP/Index Engineer | `specialized/lsp-index-engineer.md` | Especialista em Language Server Protocol e inteligencia de codigo |
| Sales Data Extraction Agent | `specialized/sales-data-extraction-agent.md` | Agente que monitora Excel e extrai metricas de vendas |
| Data Consolidation Agent | `specialized/data-consolidation-agent.md` | Agente que consolida dados de vendas em dashboards |
| Report Distribution Agent | `specialized/report-distribution-agent.md` | Agente que automatiza distribuicao de relatorios de vendas |
| Data Analytics Reporter | `specialized/data-analytics-reporter.md` | Analista de dados: transforma dados brutos em insights e dashboards |

---

## Sugestoes por perfil

### Empreendedor / Dono de negocio
1. **Growth Hacker** — estrategias de crescimento
2. **Content Creator** — conteudo para redes sociais
3. **Instagram Curator** ou **TikTok Strategist** — redes sociais especificas
4. **Finance Tracker** — controle financeiro

### Social Media / Marketing
1. **Social Media Strategist** — estrategia geral
2. **Instagram Curator** — Instagram
3. **TikTok Strategist** — TikTok
4. **Content Creator** — criacao de conteudo

### Designer
1. **UI Designer** — interfaces
2. **UX Researcher** — pesquisa com usuarios
3. **Brand Guardian** — identidade de marca
4. **Image Prompt Engineer** — gerar imagens com IA

### Desenvolvedor
1. **Frontend Developer** — frontend web
2. **Backend Architect** — backend e APIs
3. **DevOps Automator** — infraestrutura
4. **Security Engineer** — seguranca

### Gerente de Produto
1. **Sprint Prioritizer** — planejamento de sprints
2. **Trend Researcher** — pesquisa de tendencias
3. **Feedback Synthesizer** — analise de feedback
4. **Project Shepherd** — gestao de projetos

---

## Dicas de uso

- **Use um agente por conversa** — comece uma nova conversa para cada agente
- **Seja especifico** — depois de colar o agente, faca perguntas detalhadas sobre seu contexto
- **Combine agentes** — use o Growth Hacker para estrategia, depois o Content Creator para executar
- **Funciona em qualquer IA** — Claude, ChatGPT, Gemini, ou qualquer chat que aceite texto longo
