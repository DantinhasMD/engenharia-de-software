# Semestre 5 (6 disciplinas):

## Design e Arquitetura de Software
**Objetivo de engenharia:** Capacitar o engenheiro a tomar decisões arquiteturais explícitas, justificáveis e rastreáveis, equilibrando requisitos funcionais, atributos de qualidade, custo e risco técnico.

**Competências (K+S+D):**
- K: estilos arquiteturais, padrões, atributos de qualidade, trade-offs
- S: projetar arquiteturas, documentar decisões, avaliar alternativas
- D: responsabilidade técnica, pensamento sistêmico, aversão a soluções mágicas

**Ementa:** Fundamentos de arquitetura de software, estilos arquiteturais, padrões de projeto, documentação arquitetural e avaliação de trade-offs.

**Conteúdo Programático:**
- Arquitetura como decisão, não diagrama
- Atributos de qualidade (desempenho, escalabilidade, confiabilidade, segurança)
- Estilos arquiteturais (camadas, hexagonal, eventos, microserviços)
- Padrões de projeto e padrões arquiteturais
- Architectural Decision Records (ADR) e Análise de trade-offs (ATAM)

**Dependências:** Engenharia de Requisitos; Modelagem e Análise de Software; Sistemas Distribuídos (conceitos básicos)

**Entregáveis:**
- Documento de arquitetura completo e Conjunto de ADRs justificados

**Bibliografia:**
- Bass et al. — Software Architecture in Practice
- Richards & Ford — Fundamentals of Software Architecture

**Método de estudo:** Estudos de sistemas reais, revisão crítica de arquiteturas existentes, defesa técnica de decisões.

## Bancos de Dados II — Distribuição, Escala e Consistência
**Objetivo de engenharia:** Capacitar o engenheiro a projetar soluções de persistência distribuída considerando consistência, disponibilidade, particionamento e custo operacional.

**Competências (K+S+D):**
- K: CAP, modelos NoSQL, replicação, particionamento
- S: escolher tecnologias, projetar dados distribuídos
- D: pragmatismo técnico, responsabilidade com dados

**Ementa:** Bancos de dados distribuídos, modelos de consistência, replicação, particionamento e sistemas de dados modernos.

- Conteúdo Programático:
- Limites do modelo relacional centralizado
- Teorema CAP e trade-offs
- Replicação síncrona e assíncrona
- Particionamento e sharding
- Bancos NoSQL (key-value, documento, coluna)
- Consistência eventual e conflitos

**Dependências:** Bancos de Dados I; Sistemas Distribuídos

**Entregáveis:**
- Projeto de persistência distribuída
- Relatório comparativo de trade-offs

**Bibliografia:**
- Kleppmann — Designing Data-Intensive Applications

**Método de estudo:** Benchmarking, falhas simuladas, análise de sistemas reais.

## Sistemas Distribuídos
**Objetivo de engenharia:** Capacitar o engenheiro a projetar sistemas que continuam funcionando mesmo quando partes falham.

**Competências (K+S+D):**
- K: consenso, tolerância a falhas, consistência
- S: projetar sistemas distribuídos simples
- D: paranoia saudável, pensamento probabilístico

**Ementa:** Fundamentos de sistemas distribuídos, comunicação, sincronização e tolerância a falhas.

**Conteúdo Programático:**
- O que é distribuição de verdade
- Comunicação e coordenação
- Relógios lógicos
- Algoritmos de consenso
- Detecção de falhas
- Sistemas distribuídos no mundo real

**Dependências:** Redes de Computadores; Sistemas Operacionais

**Entregáveis:** Sistema distribuído funcional e Relatório de falhas induzidas

**Bibliografia:**
- Tanenbaum & van Steen — Distributed Systems

**Método de estudo:** Implementação incremental e injeção de falhas.

## Verificação e Validação de Software
**Objetivo de engenharia:** Garantir que sistemas atendam às especificações e falhem da forma menos danosa possível.

**Competências (K+S+D):**
- K: técnicas de teste, revisão e análise
- S: planejar e automatizar testes
- D: ceticismo técnico, atenção ao detalhe

**Ementa:** Técnicas de verificação e validação, testes funcionais e estruturais, automação.

**Conteúdo Programático:**
- Verificação vs validação
- Testes unitários e de integração
- TDD e BDD
- Testes de sistema e aceitação
- Revisões e inspeções
-Automação de testes

**Dependências:** Programação Concorrente; Engenharia de Requisitos

**Entregáveis:** Plano de testes completo e Pipeline de testes automatizados

**Bibliografia:**
- Jorgensen — Software Testing

**Método de estudo:** Testar sistemas defeituosos e analisar falhas reais.

## Engenharia de Segurança de Software
**Objetivo de engenharia:** Capacitar o engenheiro a projetar sistemas resilientes a ataques e falhas de segurança ao longo de todo o ciclo de vida.

**Competências (K+S+D):**
- K: ameaças, criptografia, vulnerabilidades
- S: análise de risco e mitigação
- D: mentalidade defensiva, responsabilidade ética

**Ementa:** Segurança aplicada ao ciclo de vida de software.

**Conteúdo Programático:**
- Modelagem de ameaças
- Princípios de segurança
- Criptografia aplicada
- Autenticação e autorização
- Segurança em arquitetura
- Vulnerabilidades comuns (OWASP)

**Dependências:** Redes de Computadores; Sistemas Operacionais

**Entregáveis:**
- Modelo de ameaças
- Plano de mitigação

**Bibliografia:**
- McGraw — Software Security

**Método de estudo:** Análise de ataques reais e correção de vulnerabilidades.

## Engenharia de Configuração e DevOps
**Objetivo de engenharia:** Capacitar o engenheiro a controlar, automatizar e operar sistemas de software de forma confiável.

**Competências (K+S+D):**
- K: controle de versão, CI/CD, automação
- S: projetar pipelines e ambientes
- D: disciplina operacional, previsibilidade

**Ementa:** Gerência de configuração, integração contínua e automação de deploy.

**Conteúdo Programático:**
- Controle de versão avançado
- Estratégias de branching
- CI/CD pipelines
- Automação de ambientes
- Deploy contínuo

**Dependências:** Sistemas Operacionais; V&V

**Entregáveis:**
- Pipeline CI/CD funcional
- Infraestrutura automatizada

**Bibliografia:**
- Humble & Farley — Continuous Delivery

**Método de estudo:** Operação real de sistemas com falhas induzidas.

# Semestre 6 (6 disciplinas):

## Qualidade de Software e Métricas
**Objetivo de engenharia:** Capacitar o engenheiro a definir, medir e governar a qualidade de sistemas de software complexos, conectando decisões técnicas a impactos reais em confiabilidade, custo, risco e satisfação do usuário.

**Competências (K+S+D):**
- K: modelos de qualidade (ISO/IEC 25010), métricas de produto e processo, dívida técnica, confiabilidade, manutenibilidade 
- S: definir indicadores, coletar dados, analisar métricas, tomar decisões baseadas em evidência 
- D: rigor analítico, responsabilidade técnica, pensamento sistêmico

**Ementa:** Fundamentos de qualidade de software, modelos normativos, métricas quantitativas, avaliação contínua e governança técnica em ambientes reais de desenvolvimento.

**Conteúdo Programático:**
- Conceito de qualidade em engenharia (produto vs processo)
- ISO/IEC 25010 e decomposição de atributos
- Métricas estáticas e dinâmicas de código
- Métricas de processo (lead time, throughput, defect rate)
- Dívida técnica: identificação, mensuração e gestão
- Qualidade contínua em pipelines CI/CD

**Dependências:** Verificação e Validação de Software; Engenharia de Configuração e DevOps

**Entregáveis:** Painel de métricas de qualidade; relatório técnico de avaliação de sistema real

**Bibliografia:**
- Pressman & Maxim
- McConnell – Code Complete
- ISO/IEC 25010

**Método de estudo:** Análise de sistemas reais, instrumentação de métricas, revisão crítica de decisões técnicas

## Cloud Computing e Infraestrutura como Código
**Objetivo de engenharia:** Formar engenheiros capazes de projetar, provisionar e governar infraestrutura escalável, reproduzível e auditável para sistemas de software modernos.

**Competências (K+S+D):** 
- K: modelos de serviço em cloud, virtualização, containers, redes e storage 
- S: escrever IaC, provisionar ambientes, automatizar deploys 
- D: disciplina operacional, visão de custo, responsabilidade por disponibilidade

**Ementa:** Computação em nuvem, modelos arquiteturais, automação de infraestrutura e governança técnica.

**Conteúdo Programático:**
- IaaS, PaaS, SaaS
- Infraestrutura imutável
- Terraform e CloudFormation
- Kubernetes (fundamentos)
- Gestão de custos e capacity planning
- Segurança e compliance em cloud

**Dependências:** Sistemas Distribuídos; Engenharia de Configuração e DevOps

**Entregáveis:** Infraestrutura completa descrita em código; ambiente funcional em cloud pública

**Bibliografia:**
- Kief Morris – Infrastructure as Code
- AWS Well-Architected Framework

**Método de estudo:** Construção incremental de ambientes reais, falhas induzidas, análise de custos

## Observabilidade e Confiabilidade de Sistemas (SRE)
**Objetivo de engenharia:** Capacitar o engenheiro a operar sistemas distribuídos com confiabilidade mensurável, controlando risco e falha de forma consciente.

**Competências (K+S+D):**
- K: SLI, SLO, SLA, tolerância a falhas, caos engineering 
- S: instrumentar sistemas, analisar incidentes, definir orçamentos de erro 
- D: calma sob falha, responsabilidade sistêmica, pensamento probabilístico

**Ementa:** Fundamentos de SRE, observabilidade, confiabilidade e operação de sistemas em escala.

**Conteúdo Programático:**
- Conceitos de confiabilidade
- Logs, métricas e traces
- Definição de SLOs
- Gestão de incidentes
- Postmortems sem culpabilização
- Chaos Engineering

**Dependências:** Sistemas Distribuídos; Cloud Computing e IaC

**Entregáveis:** Sistema instrumentado; relatório de incidentes e postmortem técnico

**Bibliografia:**
- Google SRE Book
- Beyer et al.

**Método de estudo:** Simulação de falhas, análise de incidentes reais, revisão técnica coletiva

## Compiladores e Linguagens de Programação
**Objetivo de engenharia:** Capacitar o engenheiro a compreender como linguagens são construídas e executadas, permitindo decisões informadas sobre desempenho, segurança e expressividade.

**Competências (K+S+D):**
- K: análise léxica, sintática e semântica, modelos de execução 
- S: construir compiladores simples, analisar linguagens 
- D: precisão, abstração rigorosa, paciência intelectual

**Ementa:** Fundamentos de compiladores, construção de linguagens e análise de execução.

**Conteúdo Programático:**
- Estrutura de compiladores
- Análise léxica e sintática
- AST e semântica
- Geração de código
- Máquinas virtuais

**Dependências:** Algoritmos e Estruturas de Dados II; Programação III

**Entregáveis:** Compilador funcional de linguagem simples; relatório técnico

**Bibliografia:**
- Aho et al. – Dragon Book
- Crafting Interpreters

**Método de estudo:** Implementação incremental, testes formais, análise comparativa

## Manutenção e Evolução de Software
**Objetivo de engenharia:** Formar engenheiros capazes de evoluir sistemas legados com segurança, previsibilidade e responsabilidade técnica.

**Competências (K+S+D):**
- K: tipos de manutenção, arquitetura evolutiva, refatoração 
- S: leitura de código legado, refatoração segura, gestão de risco 
- D: respeito ao histórico do sistema, pragmatismo técnico

**Ementa:** Fundamentos de manutenção, evolução arquitetural e gestão de sistemas vivos.

**Conteúdo Programático:**
- Tipos de manutenção
- Refatoração avançada
- Arquitetura evolutiva
- Gestão de dívida técnica
- Sistemas legados

**Dependências:** Design e Arquitetura de Software; Qualidade de Software

**Entregáveis:** Plano de evolução de sistema real; refatoração documentada

**Bibliografia:**
- Feathers – Working Effectively with Legacy Code
- Ford et al. – Building Evolutionary Architectures

**Método de estudo:** Análise de sistemas reais, refatoração guiada por testes

## Empirical Software Engineering
**Objetivo de engenharia:** Capacitar o engenheiro a investigar, medir e validar práticas de software por meio de métodos científicos aplicados.

**Competências (K+S+D):**
- K: métodos empíricos, estatística aplicada, desenho experimental 
- S: conduzir estudos, analisar dados, interpretar resultados 
- D: honestidade intelectual, pensamento crítico, ceticismo saudável

**Ementa:** Engenharia de software baseada em evidências, experimentação e análise empírica.

**Conteúdo Programático:**
- Pesquisa empírica em SE
- Estudos de caso e experimentos
- Métricas e dados reais
- Análise estatística
- Validade interna e externa

**Dependências:** Estatística e Probabilidade Aplicadas; Qualidade de Software

**Entregáveis:** Estudo empírico completo; artigo técnico

**Bibliografia:**
- Wohlin et al. – Experimentation in Software Engineering

**Método de estudo:** Condução de pesquisa aplicada, análise crítica de dados
