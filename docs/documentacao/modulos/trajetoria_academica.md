---
layout: default
title: "Módulo 4 · Trajetória Acadêmica"
---

# {{ page.title }}

> **Continuidade da formação após a evasão.** A evasão em determinado curso não implica necessariamente interrupção da trajetória educacional. O evadido pode continuar os estudos em outro curso, nível de ensino ou instituição.

O módulo Trajetória Acadêmica identifica registros de continuidade da formação educacional dos evadidos,  em nível de pós-graduação, após a evasão observada na Rede Federal.

A unidade de análise é a ocorrência de evasão, com uma por par curso-pessoa. Uma pessoa pode contribuir com ocorrências em cursos distintos. Não se aplica a deduplicação por CPF nem a seleção de um único curso evadido de maior nível.

Quando há múltiplos registros de pós-graduação, considera-se o título de maior nível, conforme a regra do respectivo indicador, preservando as ocorrências de evasão em cursos distintos.

As fontes integradas ao módulo permitem identificar determinados registros de pós-graduação *stricto sensu* realizados no Brasil e informações relacionadas a diplomas obtidos no exterior submetidos aos processos de reconhecimento registrados na Plataforma Carolina Bori.

## Organização do módulo

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 30%; text-align: center">Aba</th>
      <th style="width: 70%; text-align: center">Conteúdo</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Visão Geral</strong></td><td>Apresenta indicadores de trajetória acadêmica identificada.</td></tr>
    <tr><td><strong>Trajetórias por curso</strong></td><td>Apresenta os resultados segundo características do curso de origem.</td></tr>
    <tr><td><strong>Trajetórias por atributos</strong></td><td>Apresenta os resultados segundo características sociodemográficas.</td></tr>
    <tr><td><strong>Dinâmica das trajetórias</strong></td><td>Apresenta a situação e os tipos de percurso acadêmico observados.</td></tr>
    <tr><td><strong>Destino das trajetórias</strong></td><td>Apresenta o curso e a localização das formações posteriormente identificadas.</td></tr>
  </tbody>
</table>

## Indicadores centrais

### 01 · Total de evadidos com trajetória acadêmica identificada · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza as ocorrências de evasão, com uma por par curso-pessoa, às quais se associa pelo menos um registro acadêmico elegível nas bases utilizadas pelo módulo.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>trajetória</sub> = ∑ I(Trajetória<sub>i</sub> = 1)<br><em>i</em>: ocorrência de evasão por par curso-pessoa.<br><em>I(Trajetória<sub>i</sub> = 1)</em>: indica a existência de pelo menos um registro acadêmico elegível associado à ocorrência.</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP, CAPES e Plataforma Carolina Bori</td></tr>
  </tbody>
</table>

### 02 · Total de evadidos e total de registros de evasão · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Neste módulo, o total de evadidos corresponde ao total de registros de evasão elegíveis, com uma ocorrência por par curso-pessoa. Uma pessoa pode contribuir com mais de uma ocorrência quando possui evasões em cursos distintos.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Total de evadidos = Total de registros de evasão = Número de pares curso-pessoa com evasão elegível</td></tr>
    <tr><td><strong>Fonte</strong></td><td>PNP</td></tr>
  </tbody>
</table>

### 03 · Fluxos acadêmicos · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Representa a combinação entre o tipo de curso associado a cada evasão e o tipo de curso posteriormente identificado, preservando uma ocorrência por par curso-pessoa.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Fluxo<sub>origem → destino</sub> = ∑ Trajetórias<sub>origem → destino</sub><br>Cada trajetória contabilizada corresponde a uma ocorrência de evasão por par curso-pessoa com destino elegível identificado.</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP, CAPES e Plataforma Carolina Bori</td></tr>
  </tbody>
</table>

### 04 · Taxa de movimentação e permanência por UF · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Apresenta a distribuição territorial das ocorrências de evasão, uma por par curso-pessoa, com trajetória acadêmica posteriormente identificada.<br>A UF de origem corresponde à UF associada ao curso no qual ocorreu a evasão.<br>A UF de destino corresponde à localização da formação posteriormente identificada.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Taxa de movimentação = N(UF<sub>destino</sub> ≠ UF<sub>origem</sub>) / N<sub>trajetórias com UF válida</sub> × 100<br>Taxa de permanência = N(UF<sub>destino</sub> = UF<sub>origem</sub>) / N<sub>trajetórias com UF válida</sub> × 100<br>As contagens consideram ocorrências de evasão por par curso-pessoa, com trajetória identificada e UFs de origem e destino válidas.</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP, CAPES e Plataforma Carolina Bori</td></tr>
  </tbody>
</table>

## Indicadores desagregados

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 26%; text-align: center">Aba</th>
      <th style="width: 28%; text-align: center">Indicador</th>
      <th style="width: 46%; text-align: center">Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Visão Geral</td><td>Trajetórias acadêmicas por campus</td><td>Quantidade de ocorrências de evasão com trajetória identificada, por par curso-pessoa, segundo campus de origem.</td></tr>
    <tr><td>Visão Geral</td><td>Taxa de trajetória acadêmica por UF</td><td>Percentual de ocorrências de evasão com trajetória identificada, calculado por par curso-pessoa, segundo UF, região ou instituição.</td></tr>
    <tr><td>Trajetórias por curso</td><td>Taxa por curso</td><td>Percentual segundo o curso associado à evasão.</td></tr>
    <tr><td>Trajetórias por curso</td><td>Taxa por tipo de curso</td><td>Percentual segundo o tipo de curso de origem.</td></tr>
    <tr><td>Trajetórias por curso</td><td>Taxa por turno</td><td>Percentual segundo o turno do curso de origem.</td></tr>
    <tr><td>Trajetórias por atributos</td><td>Taxa por sexo</td><td>Percentual segundo sexo.</td></tr>
    <tr><td>Trajetórias por atributos</td><td>Taxa por faixa etária</td><td>Percentual segundo grupos etários.</td></tr>
    <tr><td>Trajetórias por atributos</td><td>Taxa por cor ou raça</td><td>Percentual segundo cor ou raça.</td></tr>
    <tr><td>Trajetórias por atributos</td><td>Taxa por ano de evasão</td><td>Percentual segundo o ano da evasão.</td></tr>
    <tr><td>Dinâmica das trajetórias</td><td>Status da trajetória</td><td>Distribuição segundo os estados registrados nas bases utilizadas.</td></tr>
    <tr><td>Dinâmica das trajetórias</td><td>Tipo de trajetória acadêmica</td><td>Classificação da relação entre o nível do curso de origem e o nível posteriormente identificado.</td></tr>
    <tr><td>Dinâmica das trajetórias</td><td>Tipo de curso realizado</td><td>Distribuição segundo o tipo de formação posteriormente identificada.</td></tr>
    <tr><td>Dinâmica das trajetórias</td><td>Fluxos acadêmicos</td><td>Distribuição das combinações entre origem e destino.</td></tr>
    <tr><td>Destino das trajetórias</td><td>Trajetórias por curso e grau acadêmico</td><td>Distribuição segundo curso e grau acadêmico de destino.</td></tr>
  </tbody>
</table>

**Fontes:** PNP, CAPES e Plataforma Carolina Bori.

## Limitações

- A ausência de registro posterior não demonstra interrupção dos estudos.
- O estudante pode ter ingressado em curso ou instituição não abrangidos pelas bases integradas ao módulo.
- As coortes também possuem diferentes tempos disponíveis para acompanhamento. Evadidos de anos mais antigos possuem maior período para apresentar uma trajetória acadêmica posterior.
