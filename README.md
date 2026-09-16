# PhytoScan 🍇🍎

Aplicativo mobile de **detecção de oídio em frutas** (uva e maçã) por **visão computacional**. O produtor fotografa a folha ou o fruto, recebe um diagnóstico com nível de confiança, acompanha o histórico e o mapa de focos na lavoura, e obtém recomendações de manejo integrado.

> Projeto desenvolvido para a atividade avaliativa **AT1 — Planejamento, Decomposição e Gestão Ágil no GitHub** da disciplina **GAPS — Fatec 2026-2**.

---

## 🎯 Visão do Produto

O oídio (*Uncinula necator* em uva e *Podosphaera leucotricha* em maçã) é uma das principais doenças fúngicas dessas culturas, podendo causar perdas de **10% a 100%** dependendo da severidade. A inspeção visual manual é trabalhosa, subjetiva e frequentemente tardia — quando os sintomas são visíveis, o controle já é mais caro e menos eficaz.

O **PhytoScan** resolve esse gargalo automatizando a detecção precoce a partir de uma simples foto, permitindo ação rápida, aplicação localizada de fungicidas e redução do uso indiscriminado de defensivos.

**Público-alvo:** pequenos e médios produtores de uva e maçã.

**Diferencial:** diagnóstico em menos de 5 segundos, com indicação de severidade (Saudável / Leve / Moderado / Severo) e recomendações de manejo integrado que priorizam controle cultural e biológico antes do químico.

---

## 👥 Papéis da Squad

| Papel | Nome | Responsabilidade |
|---|---|---|
| **Product Owner (PO)** | Ana Souza | Priorização do backlog, valor de negócio para o produtor |
| **Product Manager (PM)** | Bruno Lima | Roadmap, métricas de acurácia e adoção |
| **Desenvolvedores** | Carla, Diego, Eduarda | Implementação das histórias de usuário |

---

## 🧱 Épicos do Produto

| Código | Épico | T-Shirt Sizing |
|---|---|---|
| E1 | `[Épico] Captura e Diagnóstico de Oídio por Imagem` | **G (Grande)** |
| E2 | `[Épico] Histórico, Mapa e Alertas de Infecção` | **M (Média)** |
| E3 | `[Épico] Recomendações de Manejo Integrado` | **P (Pequeno)** |

---

## 📦 Metodologia

- **Framework:** Scrum com apoio de Kanban para gestão visual.
- **Ferramenta:** GitHub Projects (Board + Table hierárquica).
- **Fluxo Kanban:** `Backlog → Ready (DoR) → In Progress → In Review → Done (DoD)`.
- **Estimativas:**
  - Macro (Épicos): T-Shirt Sizing (PP, P, M, G, GG).
  - Micro (Histórias): Fibonacci (1, 2, 3, 5, 8 — nada ≥ 13).
- **Qualidade:** Definição de Preparado (DoR) e Definição de Pronto (DoD) aplicadas a cada história.

### Sprints planejadas

| Sprint | Período | Total planejado |
|---|---|---|
| Sprint 1 | 15/09 a 29/09 | 14 Story Points |
| Sprint 2 | 30/09 a 14/10 | 21 Story Points |

---

## 🗂️ Estrutura do Repositório
