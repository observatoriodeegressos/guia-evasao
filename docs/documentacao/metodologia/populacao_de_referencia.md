---
layout: default
title: "População de referência"
---

# {{ page.title }}

> **Entrada pelo agrupamento “Evadidos” da PNP.** A plataforma adota integralmente a classificação existente na Plataforma Nilo Peçanha como regra de entrada no universo analisado. Não redefine as situações de matrícula.

A população de referência é composta pelos estudantes classificados no agrupamento “Evadidos” da Plataforma Nilo Peçanha, em qualquer instituição da Rede Federal de Educação Profissional, Científica e Tecnológica.

A Plataforma PNP Evadidos adota integralmente o agrupamento da categoria “Evadidos” definido pela PNP.

Esse agrupamento reúne as situações de matrícula classificadas pela PNP como evasão. A plataforma não redefine individualmente essas situações para constituir sua população de referência. Ela utiliza a classificação existente na PNP como regra de entrada no universo analisado.

## Unidade de observação

A unidade inicial de observação corresponde ao vínculo entre uma pessoa e uma matrícula em determinado curso.

Essa distinção é necessária porque pessoa, matrícula, vínculo e curso representam unidades diferentes.

Uma mesma pessoa pode possuir mais de uma matrícula na Rede Federal. Também pode apresentar evasão em um curso e permanecer ou ingressar posteriormente em outro curso.

> **Por esse motivo, a classificação de uma matrícula como evasão não significa, necessariamente, que a pessoa tenha interrompido toda a sua trajetória educacional.**

## Regra do curso de maior nível

Quando uma mesma pessoa possui registros de evasão em mais de um curso no período analisado, contabiliza-se uma única ocorrência nos indicadores cuja unidade de análise é a pessoa.

Nesses casos, preserva-se o curso de maior nível de ensino. A hierarquia adotada é:

> Doutorado > Mestrado > Mestrado Profissional > Especialização Lato Sensu > Especialização Técnica > Graduação > Médio/Técnico > FIC, Qualificação Profissional > Ensino Fundamental.

Em caso de empate no nível de ensino, preserva-se o registro de evasão mais recente.

Essa regra evita a dupla contagem de pessoas na apuração dos indicadores populacionais e mantém a vinculação da pessoa ao curso de maior nível entre aqueles em que houve registro de evasão.

> **Atenção à leitura.** A aplicação dessa regra não significa que o estudante tenha concluído ou adquirido a qualificação correspondente ao nível selecionado. O nível representa exclusivamente a classificação do curso associado ao registro de evasão utilizado na análise.

## Critérios de exclusão e estrutura da base

Registros sem data de nascimento válida ou sem CPF são descartados do universo utilizado para o pareamento entre bases.

A base intermediária de evadidos, gerada a partir da PNP, preserva múltiplos registros por pessoa, com um registro para cada vínculo curso-pessoa identificado.

A deduplicação por pessoa ocorre apenas nas etapas em que o indicador utiliza a pessoa como unidade de análise.

Essa estrutura permite que análises desagregadas por curso preservem os diferentes vínculos acadêmicos da mesma pessoa. Nessas análises, aplica-se a deduplicação por curso, de modo que cada par curso-pessoa seja contabilizado uma única vez.

As demais regras estão detalhadas em [Deduplicação]({{ "/documentacao/metodologia/deduplicacao" | relative_url }}).
