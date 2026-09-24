---
layout: default
title: "Módulo 1 · Empregabilidade"
---

# {{ page.title }}

> **Inserção no mercado de trabalho formal.** Identifica a inserção dos evadidos por meio dos vínculos registrados na Relação Anual de Informações Sociais, RAIS.

O módulo Empregabilidade identifica a inserção dos evadidos no mercado de trabalho formal por meio dos vínculos registrados na Relação Anual de Informações Sociais, RAIS.

A identificação de um evadido na RAIS indica a existência de vínculo formal no período analisado.

> **A ausência de registro não deve ser interpretada automaticamente como desemprego.** O evadido pode exercer trabalho informal, atividade autônoma, atividade empresarial ou outra forma de trabalho não captada pela RAIS.

## Organização do módulo

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 28%; text-align: center">Aba</th>
      <th style="width: 72%; text-align: center">Conteúdo</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Visão Geral</strong></td><td>Reúne os principais indicadores de ocupação formal.</td></tr>
    <tr><td><strong>Ocupação por curso</strong></td><td>Apresenta os resultados segundo as características do curso associado à evasão.</td></tr>
    <tr><td><strong>Ocupação por atributos</strong></td><td>Apresenta os resultados segundo características sociodemográficas dos evadidos.</td></tr>
    <tr><td><strong>Tipologia Ocupacional</strong></td><td>Apresenta características dos vínculos, ocupações e atividades econômicas identificadas.</td></tr>
  </tbody>
</table>

## Indicadores centrais

### 01 · Total de ocupados · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza os evadidos para os quais foi identificado vínculo formal de trabalho na RAIS.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>ocupados</sub> = ∑ I(Ocupado<sub>i</sub> = 1)</td></tr>
    <tr><td><strong>Fonte</strong></td><td>PNP e RAIS</td></tr>
  </tbody>
</table>

### 02 · Total de evadidos · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza os evadidos elegíveis para o módulo de Empregabilidade, conforme as regras de identificação e deduplicação utilizadas pela plataforma.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>evadidos</sub> = ∑ Evadidos</td></tr>
    <tr><td><strong>Fonte</strong></td><td>PNP</td></tr>
  </tbody>
</table>

### 03 · Taxa de ocupação · *Quanto maior, melhor*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Indica a proporção de evadidos com vínculo formal identificado na RAIS em relação ao total de evadidos elegíveis.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Quanto maior, melhor.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Taxa de ocupação (%) = N<sub>ocupados</sub> / N<sub>evadidos</sub> × 100</td></tr>
    <tr><td><strong>Fonte</strong></td><td>PNP e RAIS</td></tr>
  </tbody>
</table>

## Indicadores desagregados

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 24%; text-align: center">Aba</th>
      <th style="width: 30%; text-align: center">Indicador</th>
      <th style="width: 46%; text-align: center">Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Visão Geral</td><td>Total de ocupados por campus</td><td>Quantidade de evadidos ocupados segundo o campus de origem.</td></tr>
    <tr><td>Visão Geral</td><td>Taxa de ocupação por UF</td><td>Percentual de evadidos com vínculo formal segundo UF, região ou instituição.</td></tr>
    <tr><td>Ocupação por curso</td><td>Taxa de ocupação por curso</td><td>Percentual de ocupados segundo o curso associado à evasão.</td></tr>
    <tr><td>Ocupação por curso</td><td>Taxa de ocupação por tipo de curso</td><td>Percentual de ocupados segundo a tipologia do curso.</td></tr>
    <tr><td>Ocupação por curso</td><td>Taxa de ocupação por turno</td><td>Percentual de ocupados segundo o turno do curso.</td></tr>
    <tr><td>Ocupação por atributos</td><td>Taxa de ocupação por sexo</td><td>Percentual de ocupados segundo sexo.</td></tr>
    <tr><td>Ocupação por atributos</td><td>Taxa de ocupação por faixa etária</td><td>Percentual de ocupados segundo grupos etários.</td></tr>
    <tr><td>Ocupação por atributos</td><td>Taxa de ocupação por cor ou raça</td><td>Percentual de ocupados segundo cor ou raça.</td></tr>
    <tr><td>Ocupação por atributos</td><td>Taxa de ocupação por ano de evasão</td><td>Percentual de ocupados segundo o ano da evasão.</td></tr>
    <tr><td>Tipologia Ocupacional</td><td>Ocupados por natureza do vínculo</td><td>Distribuição dos ocupados segundo a natureza do vínculo.</td></tr>
    <tr><td>Tipologia Ocupacional</td><td>Ocupados por tipo de ocupação e curso</td><td>Distribuição segundo a CBO e o curso associado à evasão.</td></tr>
    <tr><td>Tipologia Ocupacional</td><td>Ocupados por atividade econômica</td><td>Distribuição dos ocupados segundo a atividade econômica do estabelecimento empregador.</td></tr>
  </tbody>
</table>

**Fontes:** PNP, RAIS, CBO e CNAE.

## Limitações

- A RAIS cobre o mercado formal de trabalho.
- A ausência de registro não comprova desemprego ou ausência de atividade econômica.
- Os resultados podem ser afetados por inconsistências nos identificadores utilizados para vincular as bases.
- As comparações entre grupos devem considerar diferenças de composição e de tempo transcorrido desde a evasão.
