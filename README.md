# 🤖 IA Mentor de Carreira: Descubra Seu Futuro em Tech

Este projeto apresenta um ecossistema de **Engenharia de Prompt** projetado para atuar como um mentor especializado em transição e aceleração de carreira na área de tecnologia. O sistema utiliza uma arquitetura de **Multi-Agentes** para garantir que o diagnóstico seja separado do planejamento estratégico.

## 🚀 Como Funciona?

O sistema é dividido em dois agentes especializados que se comunicam para entregar uma experiência personalizada:

### 1. Agent 1: O Estrategista de Carreiras
*   **Função:** Realizar uma entrevista investigativa de 7 perguntas.
*   **Diferencial:** Utiliza uma **Matriz de Decisão Interna** para avaliar afinidade, demanda de mercado e tempo de *ramp-up*.
*   **Saída:** Apresenta as 3 melhores carreiras ranqueadas com justificativa baseada na experiência prévia do usuário.

### 2. Agent 2: O Planejador de Roadmaps
*   **Função:** Criar um roteiro de execução técnica.
*   **Diferencial:** Foca na **Lei de Pareto (80/20)** para garantir que o estudante foque no que realmente gera empregabilidade.
*   **Saída:** Entrega uma visão do dia a dia, mapa de skills, roadmap de 90 dias, sugestão de projeto de portfólio e até roteiro de entrevistas.

---

## 🛠️ Tecnologias Utilizadas

*   **Prompt Engineering:** Técnicas de *Role Play*, *Few-Shot Prompting* e *Chain-of-Thought*.
*   **Markdown:** Para estruturação e organização visual dos prompts.
*   **Git/GitHub:** Para versionamento e documentação do projeto.

---

## 📂 Estrutura do Repositório
```text
├── prompts/
│   ├── agente-01-estrategista.md    # Prompt do Especialista em Carreira
│   └── agente-02-planejador.md      # Prompt do Arquiteto de Roadmaps
├── exemplos/
│   └── roadmap-exemplo.md          # Exemplo de saída gerada pela IA
└── README.md                       # Documentação principal
