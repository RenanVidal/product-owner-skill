# Product Owner Skill

Uma [Agent Skill](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) para Claude que transforma qualquer briefing em escopo de produto completo e pronto para desenvolvimento, orquestrando os principais frameworks de Product Management e Product Ownership do mercado.

## O que ela faz

Ao ser ativada, a skill assume o papel de um Product Owner sênior e identifica automaticamente o tipo de tarefa para aplicar o framework correspondente:

| Tipo de Tarefa | Framework |
|---|---|
| Entender o problema / framing | Problem Statement + Problem Framing Canvas (MITRE) |
| Entender o usuário | Proto-Persona + JTBD |
| Explorar oportunidades | Opportunity Solution Tree (Teresa Torres) |
| Definir epics | Epic Hypothesis (if/then) |
| Quebrar epic em histórias | User Story Splitting (9 padrões de Richard Lawrence) |
| Escrever histórias | User Story (Mike Cohn + Gherkin) |
| Mapear jornada | User Story Mapping (Jeff Patton) |
| Priorizar backlog | Prioritization Advisor (RICE / ICE / Kano) |
| Validar hipótese antes de construir | Lean UX Canvas (Jeff Gothelf) |
| Documentar requisitos formais | PRD (10 seções) |
| Ciclo completo de discovery | Discovery Process (6 fases) |
| Planejar roadmap | Roadmap Planning (5 fases) |

## Princípios

- Nunca avançar para solução sem validar entendimento
- Problema antes de solução
- Outcomes, não outputs
- Hipóteses falsificáveis
- Slices verticais que entregam valor de ponta a ponta

## Como usar

### No Claude (apps com suporte a Skills)

Copie a pasta `product-owner/` para o diretório de skills do seu ambiente Claude. A skill ativa automaticamente quando você menciona termos como "PO", "PRD", "user stories", "roadmap", "discovery", "priorização", entre outros.

### Instalação manual

```bash
git clone https://github.com/SEU_USUARIO/product-owner-skill.git
# copie a pasta product-owner/ para o seu diretório de skills
```

## Estrutura

```
product-owner-skill/
├── README.md
├── LICENSE
└── product-owner/
    └── SKILL.md
```

## Frameworks de referência

Construído sobre o trabalho de Mike Cohn, Richard Lawrence & Peter Green (Humanizing Work), Jeff Patton, Jeff Gothelf, Tim Herbig, Teresa Torres, Clayton Christensen, MITRE, Intercom, Marty Cagan e Rob Fitzpatrick.

## Licença

MIT — veja [LICENSE](LICENSE).
