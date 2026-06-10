# 📊 SIVE — Sistema de Identificação Visual de Evasão

> Projeto Integrador — Ciência da Computação e Análise e Desenvolvimento de Sistemas
> Identificação precoce de alunos em risco de evasão no ensino médio público do Distrito Federal.

---

## 📌 Introdução do Problema

Propõe-se o desenvolvimento do **Sistema de Identificação Visual de Evasão (SIVE)**, uma solução digital centrada na visualização estratégica de dados educacionais.

Diferente dos métodos tradicionais de chamada e diários de classe — que muitas vezes escondem padrões de abandono em meio a pilhas de papel — o SIVE utiliza a visualização de dados para destacar disparidades, tendências de faltas e comportamentos de risco antes que o aluno efetivamente abandone a instituição.

### Cenário Atual e Dados

Mais de **3.700 alunos abandonaram o ensino médio** na rede pública do Distrito Federal em 2023 — um aumento de **10,25%** em relação a 2022. Em 2023, a etapa que mais registrou abandono foi o **2º ano do ensino médio no período matutino**.

A Secretaria de Educação do Distrito Federal (SEE-DF) afirma que o índice de abandono escolar é motivo de "grande preocupação", destacando dificuldades financeiras e a necessidade de trabalhar para ajudar em casa como os principais desafios enfrentados pelos estudantes.

---

## 🎯 Visão Geral do Produto

O sistema tem como principal objetivo identificar, de forma antecipada, alunos com risco de evasão, por meio da organização e apresentação clara de informações relevantes, como frequência e histórico escolar.

A solução se materializa em um **dashboard interativo e intuitivo**, que permite à equipe pedagógica visualizar rapidamente padrões de comportamento, identificar alunos em situação de risco e compreender a evolução dos indicadores ao longo do tempo.

Diferente de sistemas operacionais complexos, o SIVE tem como foco principal **transformar dados em informações visuais claras e acionáveis**, facilitando a interpretação e apoiando a tomada de decisão.

Dessa forma, o sistema atua como uma ferramenta de apoio estratégico, permitindo que a escola identifique problemas de forma mais rápida e precisa, contribuindo para a redução da evasão escolar.

---

## 🧩 Funcionalidades

O SIVE será composto pelas seguintes funcionalidades:

### Coleta e Entrada de Dados Acadêmicos
- Importação de dados (quando disponível)
- Entrada manual de frequência e notas

### Análise Automática de Risco de Evasão
- Cálculo da frequência dos alunos
- Identificação de baixa frequência e baixo desempenho
- Detecção de alunos que não compareceram desde o início das aulas
- Consideração de fatores contextuais (ex: vulnerabilidade social)

### Geração de Alertas Inteligentes
- Classificação dos alunos por nível de risco (baixo, médio, alto)
- Geração automática de alertas
- Registro dos critérios que motivaram cada alerta
- Histórico de alertas gerados

### Dashboard Visual e Interativo
- Visualização dos alunos em risco
- Segmentação por turma, turno e nível de risco
- Filtros para facilitar análise
- Exibição clara dos indicadores de evasão

### Gestão de Informações do Aluno
- Visualização do histórico acadêmico
- Registro de observações qualitativas por professores
- Análise de perfil socioeconômico (contextual)
- Registro de dados contextuais (opcional)
- Cruzamento com indicadores acadêmicos para priorização de risco

### Controle de Acesso e Privacidade
- Restrição de acesso por perfil de usuário
- Proteção de dados sensíveis
- Conformidade com diretrizes de privacidade (LGPD)

---

## 💡 Justificativa da Solução

A solução proposta se mostra adequada ao problema apresentado, pois foi desenvolvida considerando a realidade brasileira, atuando diretamente sobre uma das principais limitações identificadas no diagnóstico: a dificuldade da equipe pedagógica em visualizar, interpretar e agir com base nos dados disponíveis sobre os alunos.

Atualmente, informações relevantes como frequência e histórico escolar encontram-se dispersas ou pouco estruturadas, dificultando a identificação precoce de padrões de evasão. Nesse contexto, o SIVE se destaca ao centralizar e organizar esses dados em um dashboard visual e intuitivo, facilitando a leitura e interpretação por parte da equipe pedagógica.

Diferentemente de sistemas operacionais complexos, a proposta não busca automatizar decisões, mas sim **qualificar a tomada de decisão**, oferecendo informações claras, acessíveis e acionáveis. Isso permite que professores e gestores identifiquem rapidamente alunos em situação de risco e adotem medidas de forma mais ágil e assertiva dentro do contexto do turno matutino.

Além disso, ao transformar dados em visualizações estratégicas, o sistema reduz a dependência de análises manuais e contribui para uma gestão mais eficiente e orientada por evidências.

---

## ⚙️ Metodologia

O sistema opera em ciclos recorrentes estruturados em três etapas:

1. **Entrada de dados:** Os professores registram de forma manual, ou exportam dados de frequência e notas por disciplina durante os dias que darão aula, alimentando o sistema por meio de importação estruturada.

2. **Processamento automático:** O sistema calcula as taxas de frequência por aluno e disciplina, compara os valores com os limiares definidos — frequência inferior a 75% e nota abaixo da média mínima aprovativa — e classifica o aluno com nível de risco baixo, médio ou alto, gerando alertas direcionados ao coordenador pedagógico responsável e diretoria.

3. **Acompanhamento pedagógico:** O coordenador acessa o dashboard, visualiza os alunos sinalizados e atualiza o status de cada caso. O histórico de alertas e intervenções é mantido ao longo do semestre, conferindo rastreabilidade ao processo.

---

## 📈 Impacto Esperado

Os resultados esperados com a implementação do sistema foram organizados em indicadores de desempenho (KPIs) que abrangem duas dimensões: o impacto pedagógico produzido pela antecipação das intervenções e a qualidade operacional do sistema durante o piloto.

**Quadro 1 — Indicadores de desempenho projetados**

| KPI | Indicador | Forma de mensuração | Meta projetada |
|-----|-----------|---------------------|----------------|
| KPI-01 | Taxa de evasão semestral | Alunos evadidos ÷ total matriculados no período | Redução de 20% em relação ao baseline coletado no início do piloto |
| KPI-02 | Antecipação da identificação de risco | Alertas gerados antes do abandono ÷ total de alunos evadidos | ≥ 70% dos alunos evadidos sinalizados previamente |
| KPI-03 | Taxa de intervenção sobre alertas | Alertas com ação registrada ÷ total de alertas ativos | ≥ 80% dos alertas com ao menos uma ação registrada |
| KPI-04 | Retenção após intervenção | Alunos sinalizados que permaneceram ÷ total sinalizados | ≥ 50% de permanência entre os alunos com intervenção registrada |
| KPI-05 | Regularidade de importação de dados | Ciclos realizados ÷ ciclos previstos no período | ≥ 90% dos ciclos dentro do prazo |
| KPI-06 | Cobertura de turmas monitoradas | Turmas com dados importados ÷ total de turmas ativas | 100% das turmas ativas ao final do piloto |

*Fonte: elaboração própria (2026).*

Os indicadores KPI-01, KPI-02 e KPI-04 medem o efeito da solução sobre a permanência dos alunos e somente poderão ser verificados ao término de um semestre completo de operação. Os demais indicadores são mensuráveis ao longo do próprio piloto e fornecem evidências imediatas sobre a viabilidade operacional do sistema.

---

## ✅ Conclusão

O SIVE responde a uma necessidade concreta identificada no Brasil: a ausência de mecanismos estruturados para identificação precoce de alunos em risco de abandono. Ao centralizar dados de frequência e desempenho em um dashboard visual e intuitivo, a solução qualifica a tomada de decisão da equipe pedagógica sem exigir infraestrutura tecnológica complexa ou substituir o julgamento humano.

A viabilidade da proposta está sustentada em três aspectos:
- **Aderência à realidade operacional da instituição**, com suporte à entrada manual de dados e ciclos de importação adaptáveis à capacidade da equipe;
- **Conformidade com a LGPD**, garantindo o uso restrito dos dados a finalidades pedagógicas;
- **Escopo delimitado do MVP**, que prioriza entregas funcionais verificáveis dentro do prazo do projeto.

Os riscos identificados — resistência dos professores ao registro regular e disponibilidade da coordenação para atuar sobre os alertas — serão monitorados ao longo do piloto. O conjunto de KPIs definidos permite acompanhar tanto o impacto pedagógico quanto a adoção operacional do sistema, oferecendo evidências concretas para avaliação dos resultados ao final do semestre de implantação.

---

## 🗂️ Estrutura do Projeto

```
sive/
├── diagramas/       # Diagramas BPMN (AS IS e TO BE)
├── documentacao/    # Documentação acadêmica e técnica (DAN)
├── pitch-slides/    # Apresentação do projeto (pitch)
├── prototipo-01/    # Telas do primeiro protótipo de interface
└── prototipo-02/    # Telas do segundo protótipo de interface
```

---

## 🔒 Privacidade

Este projeto trata dados pessoais e sensíveis em contexto pedagógico e segue as diretrizes da **LGPD (Lei nº 13.709/2018)**, com uso restrito a finalidades educacionais e controle de acesso por perfil de usuário.

---

## 👩‍💻 Equipe

| Nome | Papel |
|------|-------|
| [Maria Brandão](https://github.com/MariaBrandao18) | Estudante de CC |
| [Marcela Lucy](https://github.com/lucybaia) | Estudante de ADS |
| [Dimitri Ramos](https://github.com/DimitriRamos) | Estudante de CC |

---

## 🧑‍🏫 Orientação

| Nome | Papel |
|------|-------|
| [Walner Pessoa](https://github.com/WalnerPessoa) | Professor |
| [UniCEUB](https://www.uniceub.br/) | Instituição |

---

## 🤝 Contribuição

Este é um projeto acadêmico em desenvolvimento ativo. Sugestões e colaborações são bem-vindas via [Issues](https://github.com/MariaBrandao18/sive/issues).

---

<p align="center">
  Desenvolvido com propósito social · Projeto Integrador · 2025–2026
</p>
