# Esquemas Conceituais — Aula 05: Estratégia Competitiva (Porter, 1997)

## As Cinco Forças Competitivas

```mermaid
flowchart TD
    RC[Rivalidade entre Concorrentes]

    NE[Ameaça de Novos Entrantes] --> RC
    PC[Poder de Barganha dos Compradores] --> RC
    PF[Poder de Barganha dos Fornecedores] --> RC
    PS[Ameaça de Produtos Substitutos] --> RC

    RC --> LUC[Lucratividade da Indústria]

    NE -.-> NE1[Barreiras: capital, escala, marca, canais]
    PC -.-> PC1[Concentração de compras, acesso a alternativas]
    PF -.-> PF1[Poucos fornecedores, insumos críticos]
    PS -.-> PS1[Teto implícito sobre preços praticáveis]
```

---

## Estratégias Genéricas de Porter

```mermaid
graph TD
    EG[Estratégias Genéricas]

    EG --> LC[Liderança em Custos]
    EG --> DIF[Diferenciação]
    EG --> FOC[Foco — Nicho]

    LC --> LC1[Eficiência operacional e escala]
    LC --> LC2[Preços menores com margens preservadas]

    DIF --> DIF1[Atributos de valor percebido pelo cliente]
    DIF --> DIF2[Marca, tecnologia, serviço — preço superior]

    FOC --> FOC1[Segmento específico do mercado]
    FOC --> FOC2[Pode combinar custo ou diferenciação no nicho]
```

---

## Dinâmica Estratégica — Posições Possíveis

```mermaid
flowchart LR
    ORG[Organização]

    ORG --> A[Defender-se das forças competitivas]
    ORG --> B[Alterar a estrutura da indústria a seu favor]
    ORG --> C[Antecipar mudanças estruturais do setor]

    A -.-> A1[Elevar barreiras de entrada]
    B -.-> B1[Aumentar custos de troca para compradores]
    C -.-> C1[Reposicionar-se antes da ruptura]
```

---

## Exemplos de Setores — Intensidade das Forças

```mermaid
graph TD
    subgraph Indústria do Petróleo
        P1[Alto poder dos compradores]
        P2[Forte rivalidade entre produtores]
    end

    subgraph Setor de Aço
        A1[Concorrência internacional intensa]
        A2[Pressão de produtos substitutos]
    end

    subgraph Mercado de Software Corporativo
        S1[Altos custos de troca — reduz poder do comprador]
        S2[Barreiras de entrada moderadas]
        S3[Ameaça de soluções em nuvem como substitutos]
    end
```
