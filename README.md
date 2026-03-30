# 📊 Sistema de Monitoramento de Evasão Escolar

> Projeto Integrador — Ciência da Computação e Análise e Desenvolvimento de Sistemas
> Identificação precoce de alunos em risco de evasão no CESAS — Centro de Educação para Adultos do Asa Sul, Brasília/DF.

---

## 📌 Sobre o Projeto

A evasão escolar é um dos maiores desafios das instituições públicas de ensino no Brasil. No contexto da Educação de Jovens e Adultos (EJA), esse desafio é ainda mais complexo: os fatores que levam ao abandono vão além do desempenho acadêmico e envolvem vulnerabilidade social, dificuldades de transporte, ausência de rede de apoio familiar e falta de bolsas de permanência.

Este projeto propõe um **sistema de monitoramento de permanência escolar** voltado especificamente para o **CESAS**, desenvolvido a partir de entrevista direta com a coordenação da instituição. O sistema combina indicadores acadêmicos (frequência e notas) com um perfil contextual do aluno, gerando alertas que apoiam a intervenção pedagógica e a busca ativa.

O escopo inicial cobre o **segmento EJA no turno matutino** do CESAS, com potencial de expansão para os demais segmentos e turnos.

Desenvolvido como Projeto Integrador do curso de Ciência da Computação e Análise e Desenvolvimento de Sistemas, com foco em impacto social e aplicabilidade real.

---

## 🎯 Objetivo

Apoiar a equipe pedagógica do CESAS na identificação precoce de alunos em risco de abandono, cruzando dados de frequência e desempenho acadêmico com fatores contextuais de vulnerabilidade, e disponibilizando alertas e registros de intervenção que tornem a busca ativa mais organizada e rastreável.

---

## 🏫 Contexto Institucional

O **CESAS** (Centro de Educação para Adultos do Asa Sul) é uma escola pública do Distrito Federal com foco em EJA, atendendo todos os turnos e múltiplas faixas etárias. A instituição também oferece Cursos Profissionalizantes e Ensino Fundamental.

Desafios identificados diretamente com a coordenação:

- Ausência de sistema de alerta automático — o controle depende da percepção individual dos professores
- Chamada feita em papel, sem sistema digital funcional no momento
- Alunos matriculados que nunca comparecem desde o início das aulas
- Perfis específicos de risco: alunas mães sem rede de apoio, alunos residentes no entorno do DF (Goiás) sem acesso ao passe estudantil BRB Mobilidade, alunos em situação de rua
- Ausência de creche na escola e falta de bolsas de permanência
- Busca ativa realizada via WhatsApp, sem registro formal
- Salas de apoio como recurso essencial, mas sem encaminhamento sistematizado

---

## 🧩 Funcionalidades Previstas

- Entrada manual de dados de frequência e notas (independente de sistema acadêmico externo)
- Alertas automáticos para coordenadores pedagógicos com base em frequência, notas e perfil contextual
- Alerta imediato para alunos sem presença nas primeiras semanas letivas
- Registro de observações qualitativas dos professores
- Cadastro de perfil contextual do aluno (situação familiar, transporte, vulnerabilidade social)
- Registro de busca ativa (WhatsApp, telefone, visita domiciliar) com data, responsável e resultado
- Encaminhamento formal para salas de apoio e assistência social
- Dashboard segmentado por turno e segmento educacional
- Interface voltada à tomada de decisão pedagógica

---

## 🗂️ Estrutura do Projeto

```
sistema-de-monitoramento-de-evasao-escolar/
├── docs/        # Documentação acadêmica e técnica
├── src/         # Código-fonte da solução
└── data/        # Estrutura de dados e exemplos anonimizados
```

---

## 🔒 Privacidade

Este projeto trata dados pessoais e sensíveis em contexto pedagógico — incluindo perfil socioeconômico e situação de vulnerabilidade — e segue as diretrizes da **LGPD (Lei nº 13.709/2018)**, com uso restrito a finalidades educacionais e controle de acesso por perfil de usuário.

O uso dos dados do CESAS está condicionado à autorização formal da coordenação junto à Secretaria de Educação do Distrito Federal.

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

Este é um projeto acadêmico em desenvolvimento ativo. Sugestões e colaborações são bem-vindas via [Issues](https://github.com/MariaBrandao18/sistema-de-monitoramento-de-evasao-escolar/issues).

---

<p align="center">
  Desenvolvido com propósito social · Projeto Integrador · 2025–2026
</p>
