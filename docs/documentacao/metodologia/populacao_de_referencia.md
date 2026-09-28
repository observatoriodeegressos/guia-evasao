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

A unidade de observação varia conforme o indicador. Para a taxa de evasão e a trajetória acadêmica, utiliza-se o número de evasões identificado a partir dos registros da PNP, com uma ocorrência por par curso-pessoa. Assim, uma pessoa pode contribuir com mais de uma evasão quando abandona cursos distintos.

Para os indicadores de empregabilidade, salários, empreendedorismo e produção científica, a unidade de observação é a pessoa, identificada pelo CPF. O cruzamento com a RAIS, a Receita Federal e a Plataforma Lattes ocorre por esse identificador. Por isso, a pessoa é contada uma única vez em cada indicador, mesmo que tenha evadido de mais de um curso.

> **Por esse motivo, a evasão em uma matrícula não significa, necessariamente, que a pessoa interrompeu sua trajetória educacional. Ela pode permanecer em outro curso ou ingressar posteriormente em uma nova formação**.


## Regra do curso de maior nível

A regra do curso de maior nível aplica-se aos indicadores de empregabilidade, salários, empreendedorismo e produção científica. Nesses indicadores, a unidade de análise é a pessoa. Se ela evadiu de mais de um curso no período analisado, seu CPF é contabilizado uma única vez.

Para associar essa pessoa a um curso nos recortes dos indicadores, seleciona-se o curso de maior nível entre aqueles com registro de evasão. Adota-se a seguinte hierarquia:

> Doutorado > Mestrado > Mestrado Profissional > Especialização Lato Sensu > Especialização Técnica > Graduação > Médio/Técnico > FIC, Qualificação Profissional > Ensino Fundamental.

Se houver mais de uma evasão no mesmo nível de ensino, seleciona-se o registro de evasão mais recente.

Essa seleção não se aplica à taxa de evasão nem à trajetória acadêmica. Nessas análises, preserva-se uma ocorrência de evasão por par curso-pessoa, mantendo os registros em cursos distintos.

> **Atenção à leitura.** O nível selecionado identifica o curso usado para classificar a pessoa nos recortes dos indicadores. Ele não indica conclusão do curso nem permite atribuir ao curso o resultado observado nas bases externas.


## Critérios de exclusão e estrutura da base

Registros sem CPF ou com data de nascimento inválida são excluídos da base analítica. Eles não entram no pareamento com bases externas nem no numerador ou denominador da taxa de evasão.

A deduplicação por pessoa ocorre apenas nos indicadores de empregabilidade, salários, empreendedorismo e produção científica.

Essa estrutura preserva os diferentes vínculos acadêmicos da mesma pessoa na taxa de evasão e na trajetória acadêmica, com uma ocorrência de evasão por par curso-pessoa. Nos indicadores calculados por pessoa, os recortes por curso utilizam exclusivamente o curso selecionado pela regra do maior nível.

As demais regras estão detalhadas em [Deduplicação]({{ "/documentacao/metodologia/deduplicacao" | relative_url }}).
