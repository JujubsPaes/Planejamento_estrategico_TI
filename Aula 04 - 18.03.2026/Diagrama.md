# Esquemas Conceituais — Aula 04: TI nas Organizações

## Estrutura Interna da Área de TI

```mermaid
flowchart TD
    TI[Área de TI]

    TI --> INF[Infraestrutura]
    TI --> DEV[Desenvolvimento de Sistemas]
    TI --> SUP[Suporte Técnico]
    TI --> SEG[Segurança da Informação]
    TI --> GD[Gestão de Dados]

    INF --> INF1[Servidores, redes, armazenamento]
    DEV --> DEV1[Criação e manutenção de softwares]
    SUP --> SUP1[Atendimento e resolução de incidentes]
    SEG --> SEG1[Políticas, controles e conformidade]
    GD --> GD1[Qualidade, disponibilidade e BI]
```

---

## Modelos de Organização da TI

```mermaid
graph TD
    subgraph Centralizado
        C1[Controle unificado] --> C2[Padronização tecnológica]
        C2 --> C3[Maior governança e segurança]
    end

    subgraph Descentralizado
        D1[Autonomia por unidade] --> D2[Flexibilidade operacional]
        D2 --> D3[Proximidade com as necessidades do negócio]
    end

    subgraph Híbrido
        H1[Infraestrutura central] --> H2[Autonomia parcial por área]
        H2 --> H3[Equilíbrio entre controle e flexibilidade]
    end
```

---

## Gestão de Serviços de TI — Ciclo ITIL

```mermaid
flowchart LR
    PLN[Planejamento] --> ENT[Entrega do Serviço]
    ENT --> MON[Monitoramento]
    MON --> MEL[Melhoria Contínua]
    MEL --> PLN

    ENT -.-> S1[Gerenciamento de incidentes]
    ENT -.-> S2[Gerenciamento de mudanças]
    ENT -.-> S3[Gerenciamento de níveis de serviço]
```

---

## Dados da Pesquisa FGV (2025) — Uso de TI nas Empresas Brasileiras

```mermaid
pie title Adoção de Tecnologias nas Empresas Brasileiras
    "ERP — Sistemas Integrados (91%)" : 91
    "Computação em Nuvem (52%)" : 52
    "Demais tecnologias" : 30
```

---

## Governança de TI — Objetivos e Instrumentos

```mermaid
flowchart TD
    GOV[Governança de TI]

    GOV --> O1[Uso eficiente dos recursos tecnológicos]
    GOV --> O2[Gestão de riscos tecnológicos]
    GOV --> O3[Alinhamento TI–Objetivos organizacionais]

    GOV --> F1[COBIT 2019]
    GOV --> F2[ITIL]
    GOV --> F3[ISO/IEC 27001 — Segurança da Informação]
```
