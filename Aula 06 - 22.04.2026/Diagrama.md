# Esquemas Conceituais — Aula 06: CRM (Customer Relationship Management)

## Objetivos do CRM nas Organizações

```mermaid
flowchart TD
    CRM[CRM como Estratégia Organizacional]

    CRM --> O1[Organizar informações sobre clientes]
    CRM --> O2[Qualificar o relacionamento]
    CRM --> O3[Aumentar eficiência comercial]

    O1 --> O1a[Centralização de dados]
    O1 --> O1b[Histórico completo de interações]

    O2 --> O2a[Atendimento personalizado]
    O2 --> O2b[Antecipação de necessidades]

    O3 --> O3a[Leads qualificados e pipeline estruturado]
    O3 --> O3b[Decisões orientadas por dados]
```

---

## Tipos de CRM

```mermaid
graph TD
    subgraph CRM Operacional
        OP1[Automação de vendas]
        OP2[Campanhas automáticas de marketing]
        OP3[Gestão padronizada de contatos]
    end

    subgraph CRM Analítico
        AN1[Segmentação comportamental de clientes]
        AN2[Previsão de churn e lead scoring]
        AN3[Análise de padrões de compra]
    end

    subgraph CRM Colaborativo
        CO1[Integração entre equipes e canais]
        CO2[Histórico compartilhado de atendimento]
        CO3[Experiência omnichannel]
    end
```

---

## Funil de Vendas e Jornada do Cliente

```mermaid
flowchart TD
    T[Topo do Funil] --> |Visitantes e descoberta do problema| M[Meio do Funil]
    M --> |Leads qualificados e avaliação de alternativas| F[Fundo do Funil]
    F --> |Decisão de compra| C[Cliente]
    C --> |Relacionamento contínuo| R[Retenção e LTV]

    T -.-> T1[Interesse inicial]
    M -.-> M1[Consideração de soluções]
    F -.-> F1[Oportunidade comercial ativa]
    R -.-> R1[Upsell, cross-sell, fidelização]
```

---

## Principais Métricas de CRM

```mermaid
graph LR
    subgraph Aquisição
        CAC[CAC — Custo de Aquisição de Cliente]
        CONV[Taxa de Conversão]
    end

    subgraph Valor
        LTV[LTV — Lifetime Value]
        TM[Ticket Médio]
    end

    subgraph Retenção
        CH[Churn — Taxa de Abandono]
        UP[Upsell e Cross-sell]
    end

    CAC --> EQ[Equilíbrio Comercial]
    LTV --> EQ
    CH --> EQ
```

---

## Integração TI, Marketing e Comercial no CRM

```mermaid
graph LR
    TI[TI] --> |Integra sistemas, centraliza dados, automatiza| CRM[Plataforma CRM]
    MKT[Marketing] --> |Gera e nutre leads, segmenta públicos| CRM
    COM[Comercial] --> |Gerencia pipeline e conversão| CRM

    CRM --> DEC[Decisões estratégicas orientadas por dados]
    CRM --> EXP[Experiência consistente para o cliente]
```
