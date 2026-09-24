---
layout: default
title: "Módulo 5 · Produção Científica"
---

# {{ page.title }}

> **Atividade técnico-científica registrada no Lattes.** Os resultados dependem da existência do currículo, da vinculação correta entre a pessoa e o registro e da atualização das informações pelo titular.

O módulo Produção Científica identifica atividades técnico-científicas dos evadidos a partir das informações registradas nos Currículos Lattes identificados pela plataforma.

## Organização do módulo

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 28%; text-align: center">Aba</th>
      <th style="width: 72%; text-align: center">Conteúdo</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Lattes</strong></td><td>Apresenta os indicadores relacionados à identificação de Currículo Lattes.</td></tr>
    <tr><td><strong>Produção</strong></td><td>Apresenta a quantidade de produções identificadas.</td></tr>
    <tr><td><strong>Produção por curso</strong></td><td>Apresenta os resultados segundo características do curso associado à evasão.</td></tr>
    <tr><td><strong>Tipo de produção</strong></td><td>Detalha as categorias e os tipos de produção registrados.</td></tr>
  </tbody>
</table>

## Indicadores centrais

### 01 · Total de evadidos com Currículo Lattes · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza os evadidos para os quais foi identificado Currículo Lattes.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>Lattes</sub> = ∑ I(Lattes<sub>i</sub> = 1)</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e Plataforma Lattes</td></tr>
  </tbody>
</table>

### 02 · Total de evadidos · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza os evadidos elegíveis para o módulo após aplicação das regras de deduplicação.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>evadidos</sub> = ∑ Evadidos</td></tr>
    <tr><td><strong>Fonte</strong></td><td>PNP</td></tr>
  </tbody>
</table>

### 03 · Taxa de evadidos com Currículo Lattes · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Indica a proporção de evadidos para os quais foi identificado Currículo Lattes.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Taxa Lattes (%) = N<sub>evadidos com Lattes</sub> / N<sub>evadidos</sub> × 100</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e Plataforma Lattes</td></tr>
  </tbody>
</table>

### 04 · Total de produções · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza as produções registradas nos Currículos Lattes identificados e classificadas segundo as categorias utilizadas pela plataforma. As produções são agrupadas em produção bibliográfica, produção técnica e propriedade intelectual.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Total de produções = ∑ P<sub>bibliográfica</sub> + ∑ P<sub>técnica</sub> + ∑ P<sub>propriedade intelectual</sub></td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e Plataforma Lattes</td></tr>
  </tbody>
</table>

### 05 · Evadidos com produção · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza os evadidos que possuem pelo menos uma produção elegível registrada no Currículo Lattes.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>evadidos com produção</sub> = ∑ I(Produção<sub>i</sub> ≥ 1)</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e Plataforma Lattes</td></tr>
  </tbody>
</table>

### 06 · Média de produção · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Indica o número médio de produções entre os evadidos que possuem pelo menos uma produção registrada.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Média de produção = Total de produções / N<sub>evadidos com produção</sub></td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e Plataforma Lattes</td></tr>
  </tbody>
</table>

## Indicadores desagregados

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 22%; text-align: center">Aba</th>
      <th style="width: 32%; text-align: center">Indicador</th>
      <th style="width: 46%; text-align: center">Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Lattes</td><td>Taxa de evadidos com Lattes por curso</td><td>Percentual segundo o curso associado à evasão.</td></tr>
    <tr><td>Lattes</td><td>Taxa de evadidos com Lattes por UF</td><td>Percentual segundo UF, região ou instituição.</td></tr>
    <tr><td>Lattes</td><td>Taxa de evadidos com Lattes por tipo de curso</td><td>Percentual segundo a tipologia do curso.</td></tr>
    <tr><td>Produção</td><td>Produção por campus</td><td>Quantidade de produções segundo campus.</td></tr>
    <tr><td>Produção</td><td>Produção por UF</td><td>Quantidade de produções segundo UF, região ou instituição.</td></tr>
    <tr><td>Produção por curso</td><td>Número de produções por curso</td><td>Quantidade segundo o curso associado à evasão.</td></tr>
    <tr><td>Produção por curso</td><td>Número de produções por tipo de curso</td><td>Quantidade segundo a tipologia do curso.</td></tr>
    <tr><td>Produção por curso</td><td>Número de produções por turno</td><td>Quantidade segundo o turno.</td></tr>
    <tr><td>Tipo de produção</td><td>Número de produções por categoria</td><td>Quantidade de produções bibliográficas, técnicas e de propriedade intelectual.</td></tr>
    <tr><td>Tipo de produção</td><td>Produção bibliográfica por tipo</td><td>Quantidade segundo tipos como artigos, livros, capítulos e trabalhos em eventos.</td></tr>
    <tr><td>Tipo de produção</td><td>Produção técnica por tipo</td><td>Quantidade segundo tipos como relatórios, softwares, produtos tecnológicos e trabalhos técnicos.</td></tr>
    <tr><td>Tipo de produção</td><td>Propriedade intelectual por tipo</td><td>Quantidade segundo as categorias adotadas na plataforma.</td></tr>
  </tbody>
</table>

**Fontes:** PNP e Plataforma Lattes.

## Limitações

- Nem todos os evadidos possuem Currículo Lattes.
- Entre os currículos identificados, o grau de atualização pode variar.
- A ausência de produção registrada não comprova ausência de atividade científica, técnica ou tecnológica.
- A quantidade de produções também não constitui, isoladamente, medida de qualidade ou impacto científico.
- Comparações entre grupos devem considerar diferenças de nível de ensino, área de formação, idade e tempo transcorrido desde a evasão.
