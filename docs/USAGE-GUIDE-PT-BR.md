# Guia de Uso dos Agentes - The Agency

> Como instalar, ativar e usar os 68 agentes especializados deste repositório.

---

## O Que São Esses Agentes?

Cada agente é um arquivo Markdown com personalidade, expertise e workflows definidos. Eles funcionam como **especialistas de IA** que você ativa dentro de ferramentas de desenvolvimento como Claude Code, Cursor, Aider, entre outras.

Não são código executável — são **prompts estruturados** que transformam a IA em um especialista com voz, processos e entregas concretas.

---

## Instalação Rápida

### Opção 1: Claude Code (Recomendado)

```bash
# Copie os agentes para o diretório do Claude Code
cp -r engineering/ design/ marketing/ product/ project-management/ \
      testing/ support/ spatial-computing/ specialized/ ~/.claude/agents/

# Ou use o script de instalação automática
./scripts/install.sh --tool claude-code
```

### Opção 2: Cursor, Aider, Windsurf, Gemini CLI ou OpenCode

```bash
# Passo 1: Gere os arquivos no formato da ferramenta
./scripts/convert.sh

# Passo 2: Instale (detecta ferramentas automaticamente)
./scripts/install.sh

# Ou instale para uma ferramenta específica
./scripts/install.sh --tool cursor
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
./scripts/install.sh --tool opencode
./scripts/install.sh --tool gemini-cli
```

### Opção 3: Uso Manual (Qualquer LLM)

Abra o arquivo `.md` do agente desejado e cole o conteúdo no início da conversa com qualquer modelo de IA (ChatGPT, Gemini, Claude, etc.).

---

## Como Ativar um Agente

Após a instalação, basta **referenciar o agente por nome** na sua sessão:

```
Ative o Frontend Developer e me ajude a construir um componente React.
```

```
Use o Backend Architect para projetar a API do meu sistema de pedidos.
```

```
Aplique o Reality Checker para verificar se esta feature está pronta para produção.
```

---

## Divisões e Agentes Disponíveis

### Engineering (11 agentes)
| Agente | Quando Usar |
|--------|------------|
| Frontend Developer | Apps web modernos, React/Vue/Angular, performance |
| Backend Architect | APIs, microserviços, banco de dados, escalabilidade |
| Mobile App Builder | Apps iOS/Android, React Native, Flutter |
| AI Engineer | Modelos ML, pipelines de dados, integração com IA |
| DevOps Automator | CI/CD, infraestrutura, automação de deploy |
| Rapid Prototyper | MVPs rápidos, provas de conceito, hackathons |
| Senior Developer | Laravel/Livewire, padrões avançados |
| Security Engineer | Modelagem de ameaças, revisão de código seguro |
| Data Engineer | Pipelines de dados, ETL, analytics |
| Technical Writer | Documentação técnica |
| Autonomous Optimization Architect | Sistemas auto-otimizáveis |

### Design (8 agentes)
| Agente | Quando Usar |
|--------|------------|
| UI Designer | Design visual, design systems, bibliotecas de componentes |
| UX Researcher | Testes com usuários, análise de comportamento |
| UX Architect | Arquitetura técnica de UX, sistemas CSS |
| Brand Guardian | Identidade de marca, consistência visual |
| Visual Storyteller | Narrativas visuais, conteúdo multimídia |
| Whimsy Injector | Microinterações, personalidade, momentos de encantamento |
| Image Prompt Engineer | Criação de prompts para geração de imagens com IA |
| Inclusive Visuals Specialist | Representação diversa em visuais |

### Marketing (11 agentes)
| Agente | Quando Usar |
|--------|------------|
| Growth Hacker | Aquisição de usuários, loops virais |
| Content Creator | Conteúdo multiplataforma, calendários editoriais |
| Twitter Engager | Engajamento em tempo real, thought leadership |
| TikTok Strategist | Conteúdo viral, otimização de algoritmo |
| Instagram Curator | Storytelling visual, construção de comunidade |
| Reddit Community Builder | Engajamento autêntico, conteúdo de valor |
| App Store Optimizer | ASO, otimização de conversão em app stores |
| Social Media Strategist | Estratégia cross-platform |
| Xiaohongshu Specialist | Conteúdo lifestyle (mercado chinês) |
| WeChat Official Account Manager | Engajamento de assinantes (mercado chinês) |
| Zhihu Strategist | Thought leadership (mercado chinês) |

### Product (4 agentes)
| Agente | Quando Usar |
|--------|------------|
| Sprint Prioritizer | Planejamento ágil, priorização de features |
| Trend Researcher | Inteligência de mercado, análise competitiva |
| Feedback Synthesizer | Análise de feedback de usuários |
| Behavioral Nudge Engine | Otimização de conversão, psicologia comportamental |

### Project Management (5 agentes)
| Agente | Quando Usar |
|--------|------------|
| Studio Producer | Orquestração de alto nível, gestão de portfólio |
| Project Shepherd | Coordenação cross-funcional, gestão de cronograma |
| Studio Operations | Eficiência operacional, otimização de processos |
| Experiment Tracker | Testes A/B, validação de hipóteses |
| Senior Project Manager | Escopo realista, conversão de tarefas |

### Testing (8 agentes)
| Agente | Quando Usar |
|--------|------------|
| Evidence Collector | QA baseado em screenshots, prova visual |
| Reality Checker | Certificação baseada em evidências, quality gates |
| Test Results Analyzer | Avaliação de testes, análise de métricas |
| Performance Benchmarker | Testes de performance, otimização |
| API Tester | Validação de APIs, testes de integração |
| Tool Evaluator | Avaliação de tecnologias, seleção de ferramentas |
| Workflow Optimizer | Análise de processos, otimização de workflows |
| Accessibility Auditor | Auditoria WCAG, testes de acessibilidade |

### Support (6 agentes)
| Agente | Quando Usar |
|--------|------------|
| Support Responder | Atendimento ao cliente, resolução de problemas |
| Analytics Reporter | Análise de dados, dashboards, insights |
| Finance Tracker | Planejamento financeiro, gestão de orçamento |
| Infrastructure Maintainer | Confiabilidade de sistemas, otimização de performance |
| Legal Compliance Checker | Compliance, regulações, revisão legal |
| Executive Summary Generator | Comunicação para C-suite, resumos estratégicos |

### Spatial Computing (6 agentes)
| Agente | Quando Usar |
|--------|------------|
| XR Interface Architect | Design de interação espacial, UX imersiva |
| macOS Spatial/Metal Engineer | Swift, Metal, 3D de alta performance |
| XR Immersive Developer | WebXR, AR/VR no navegador |
| XR Cockpit Interaction Specialist | Controles baseados em cockpit |
| visionOS Spatial Engineer | Desenvolvimento para Apple Vision Pro |
| Terminal Integration Specialist | Integração com terminal, ferramentas CLI |

### Specialized (9 agentes)
| Agente | Quando Usar |
|--------|------------|
| Agents Orchestrator | Coordenação multi-agente, gestão de workflows |
| Data Analytics Reporter | Business intelligence, insights de dados |
| LSP/Index Engineer | Language Server Protocol, code intelligence |
| Sales Data Extraction Agent | Monitoramento Excel, métricas de vendas |
| Data Consolidation Agent | Agregação de dados, dashboards |
| Report Distribution Agent | Distribuição automatizada de relatórios |
| Agentic Identity & Trust Architect | Identidade de agentes, autenticação, confiança |
| Cultural Intelligence Strategist | Comunicação cross-cultural |
| Developer Advocate | Relações com desenvolvedores, advocacy |

---

## Combinando Agentes (NEXUS)

O sistema **NEXUS** permite orquestrar múltiplos agentes em pipelines estruturados.

### Três Modos de Operação

| Modo | Agentes | Prazo | Uso |
|------|---------|-------|-----|
| **NEXUS-Full** | Todos os 68 | 12-24 semanas | Ciclo completo de produto |
| **NEXUS-Sprint** | 15-25 | 2-6 semanas | Feature ou MVP |
| **NEXUS-Micro** | 5-10 | 1-5 dias | Tarefa específica |

### Exemplo: MVP de Startup (NEXUS-Sprint)

```
1. Ative o Trend Researcher → Pesquisa de mercado e validação
2. Ative o Backend Architect → Arquitetura da API
3. Ative o Frontend Developer → Interface do usuário
4. Ative o Reality Checker → Verificação de qualidade
5. Ative o Growth Hacker → Estratégia de lançamento
```

Para usar NEXUS, consulte:
- `strategy/QUICKSTART.md` — Guia de ativação em 5 minutos
- `strategy/playbooks/` — Playbooks por fase do projeto
- `strategy/runbooks/` — Cenários prontos (startup MVP, feature enterprise, etc.)

---

## Exemplos Prontos

O diretório `examples/` contém workflows completos:

- **`nexus-spatial-discovery.md`** — Descoberta de produto com 8 agentes em paralelo
- **`workflow-startup-mvp.md`** — Construção de MVP em 4-6 semanas
- **`workflow-landing-page.md`** — Criação de landing page

---

## Ferramentas Suportadas

| Ferramenta | Formato | Ativação |
|------------|---------|----------|
| Claude Code | `.md` (nativo) | Referência direta por nome |
| Cursor | `.mdc` rules | `@nome-do-agente` |
| Aider | `CONVENTIONS.md` | "Use o agente [Nome]" |
| Windsurf | `.windsurfrules` | Referência no Cascade |
| OpenCode | `.md` | Referência direta |
| Gemini CLI | Extension | Referência por extensão |
| Antigravity (Gemini) | `SKILL.md` | `@agency-nome-do-agente` |

---

## Dicas de Uso

1. **Comece simples**: Ative um agente por vez até se familiarizar
2. **Seja específico**: Diga exatamente o que precisa — "Construa um componente de login com React e Tailwind"
3. **Combine agentes**: Use o Frontend Developer para construir e o Reality Checker para validar
4. **Use os exemplos**: Os workflows em `examples/` mostram combinações comprovadas
5. **Personalize**: Cada agente é um arquivo Markdown — edite para adaptar ao seu contexto
