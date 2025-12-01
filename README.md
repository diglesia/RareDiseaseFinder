# RareDiseaseFinder
Rare Disease Finder analyzes patient data against a specialized knowledge base to suggest and rank potential rare disease diagnoses

```mermaid
graph TD
    
    A[Patient Data Input] --> B{Data Processing & Standardization}
    B --> C[Rare Disease Knowledge Base]
    B --> D{Matching & Scoring Algorithm}
    C --> D
    D --> E[Ranking Module]
    E --> F[Output & Additional Information]

    %% Descriptions for each node
    A -.-> |Symptoms, History, Test Results|;
    B -.-> |Normalization, Ontology Mapping (UMLS, Orphanet)|;
    C -.-> |Disease Profiles, Symptoms, Genes, Prevalence, Treatments|;
    D -.-> |ML Models, Rule-based Reasoning, Probability Calculation|;
    E -.-> |Prioritized List of Candidate Diagnoses|;
    F -.-> |Suggested Rare Disease, Justification, References (Trials, Specialists)|;

    style A fill:#D4E6F1,stroke:#3498DB,stroke-width:2px,color:#2C3E50
    style B fill:#D4E6F1,stroke:#3498DB,stroke-width:2px,color:#2C3E50
    style C fill:#D4E6F1,stroke:#3498DB,stroke-width:2px,color:#2C3E50
    style D fill:#D4E6F1,stroke:#3498DB,stroke-width:2px,color:#2C3E50
    style E fill:#D4E6F1,stroke:#3498DB,stroke-width:2px,color:#2C3E50
    style F fill:#D4E6F1,stroke:#3498DB,stroke-width:2px,color:#2C3E50

    classDef default fill:#F2F2F2,stroke:#333,stroke-width:1px,color:#000
```
