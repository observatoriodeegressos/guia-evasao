---
layout: default
title: "Anonimização e LGPD"
---

# {{ page.title }}

> **Proteção de dados pessoais em todas as etapas.** As medidas adotadas atendem aos princípios de finalidade, necessidade, segurança e prevenção previstos na Lei nº 13.709/2018, Lei Geral de Proteção de Dados Pessoais.

A Plataforma PNP Evadidos adota medidas de proteção de dados pessoais destinadas a atender aos princípios de finalidade, necessidade, segurança e prevenção previstos na <a href="https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm" target="_blank">Lei nº 13.709/2018</a>, Lei Geral de Proteção de Dados Pessoais.

## Pareamento com validação de consistência

O cruzamento entre a PNP e as demais bases é realizado por chave de identificação individual, utilizando o CPF, em ambiente de processamento seguro e com acesso restrito.

O identificador pessoal utilizado para o pareamento não integra os dados disponibilizados ao usuário final.

Após as etapas necessárias de vinculação e validação, os registros utilizados para análise passam a ser referenciados por chaves internas sem exposição do identificador pessoal.

## Divulgação exclusivamente agregada

Nenhum dado individual é exibido nos painéis públicos da plataforma.

Os indicadores são disponibilizados na forma de contagens, proporções, taxas, médias, medianas ou outras medidas agregadas correspondentes aos grupos de análise.

## Anonimização dos dados disponibilizados

Os dados utilizados na camada de visualização não apresentam campos de identificação direta, como nome, CPF ou data de nascimento completa.

A separação entre a camada de identificação utilizada no processo de integração e a camada analítica reduz o risco de exposição de informações pessoais.

## Supressão de células pequenas

Quando determinado cruzamento resulta em frequência inferior ao limiar mínimo definido para divulgação, com **n < 5**, o valor é suprimido ou agregado em categoria residual.

Essa regra reduz o risco de identificação indireta de indivíduos a partir da combinação de características pouco frequentes.

## Limitação de cruzamentos sensíveis

A plataforma restringe combinações de filtros capazes de produzir grupos com número reduzido de indivíduos.

Assim, cruzamentos simultâneos envolvendo características como instituição, campus, curso, raça ou cor, faixa etária e renda podem ter sua granularidade limitada quando resultarem em denominadores pequenos.

> **Essas medidas buscam conciliar a utilidade analítica dos indicadores com a proteção dos dados pessoais** utilizados no processo de integração das bases.
