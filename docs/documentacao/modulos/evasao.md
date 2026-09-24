---
layout: default
title: "Aba Evasão"
---

# {{ page.title }}

> **População de origem da plataforma.** Os dados têm origem na Plataforma Nilo Peçanha e permitem analisar a ocorrência da evasão segundo características dos estudantes, cursos e instituições da Rede Federal.

A aba Evasão apresenta a população de origem da Plataforma PNP Evadidos.

## Organização da aba

A aba está organizada em quatro subabas:

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 28%; text-align: center">Subaba</th>
      <th style="width: 72%; text-align: center">Conteúdo</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Visão Geral</strong></td><td>Apresenta o total de matriculados, o total de evadidos, a taxa de evasão, a distribuição da taxa segundo recortes territoriais e a localização dos registros por campus.</td></tr>
    <tr><td><strong>Evasão por curso</strong></td><td>Apresenta os resultados segundo curso, tipo de curso e turno.</td></tr>
    <tr><td><strong>Evasão por atributo</strong></td><td>Apresenta a taxa de evasão segundo sexo, faixa etária, cor ou raça e ano da evasão.</td></tr>
    <tr><td><strong>Evasão por categoria</strong></td><td>Permite comparar categorias sociodemográficas entre diferentes anos de evasão.</td></tr>
  </tbody>
</table>

## Indicadores centrais

### 01 · Total de matriculados · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza as matrículas que compõem a população utilizada como referência para os indicadores da aba Evasão.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Curso</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>matriculados</sub> = ∑ Matrículas</td></tr>
    <tr><td><strong>Fonte</strong></td><td>Plataforma Nilo Peçanha</td></tr>
  </tbody>
</table>

### 02 · Total de evadidos · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza os registros classificados como evasão entre as matrículas pertencentes à população analisada.</td></tr>
    <tr><td><strong>Observação</strong></td><td>O indicador representa registros de evasão. Não se deve pressupor que cada ocorrência corresponda necessariamente a uma pessoa distinta.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Curso</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>evadidos</sub> = ∑ I(Evasão<sub>i</sub> = 1)<br><em>I(Evasão<sub>i</sub> = 1)</em>: identifica as matrículas classificadas como evasão segundo os critérios adotados pela plataforma.</td></tr>
    <tr><td><strong>Fonte</strong></td><td>Plataforma Nilo Peçanha</td></tr>
  </tbody>
</table>

### 03 · Taxa de evasão · *Quanto menor, melhor*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Indica a proporção de registros classificados como evasão em relação à população de matrículas considerada no cálculo.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Quanto menor, melhor.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Curso</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Taxa de evasão (%) = N<sub>evadidos</sub> / N<sub>matriculados</sub> × 100<br><em>N<sub>evadidos</sub></em>: número de registros classificados como evasão.<br><em>N<sub>matriculados</sub></em>: número de matrículas utilizadas como população de referência.</td></tr>
    <tr><td><strong>Fonte</strong></td><td>Plataforma Nilo Peçanha</td></tr>
  </tbody>
</table>

## Indicadores desagregados

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 22%; text-align: center">Subaba</th>
      <th style="width: 30%; text-align: center">Indicador</th>
      <th style="width: 48%; text-align: center">Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Visão Geral</td><td>Taxa de evadidos por UF</td><td>Apresenta a taxa de evasão segundo o recorte territorial selecionado no campo “Detalhar por”.</td></tr>
    <tr><td>Visão Geral</td><td>Total de evadidos por campus</td><td>Apresenta a distribuição dos registros de evasão segundo os campi da Rede Federal.</td></tr>
    <tr><td>Evasão por curso</td><td>Taxa de evasão por curso</td><td>Apresenta matriculados, evadidos e taxa de evasão para cada curso.</td></tr>
    <tr><td>Evasão por curso</td><td>Taxa de evasão por tipo de curso</td><td>Apresenta a taxa de evasão segundo o tipo de curso.</td></tr>
    <tr><td>Evasão por curso</td><td>Taxa de evasão por turno</td><td>Apresenta a taxa de evasão segundo o turno da oferta.</td></tr>
    <tr><td>Evasão por atributo</td><td>Taxa de evasão por sexo</td><td>Apresenta a taxa de evasão segundo sexo.</td></tr>
    <tr><td>Evasão por atributo</td><td>Taxa de evasão por faixa etária</td><td>Apresenta a taxa de evasão segundo os grupos etários adotados no painel.</td></tr>
    <tr><td>Evasão por atributo</td><td>Taxa de evasão por cor ou raça</td><td>Apresenta a taxa de evasão segundo as categorias de cor ou raça.</td></tr>
    <tr><td>Evasão por atributo</td><td>Taxa de evasão por ano de evasão</td><td>Apresenta a evolução da taxa segundo o ano do registro de evasão.</td></tr>
    <tr><td>Evasão por categoria</td><td>Taxa de evadidos por categoria e ano</td><td>Permite comparar categorias de sexo, faixa etária e cor ou raça entre até três anos selecionados.</td></tr>
  </tbody>
</table>

**Fonte:** Plataforma Nilo Peçanha.

## Interpretação

O total de evadidos mede volume. A taxa de evasão mede a ocorrência relativa à população utilizada como referência. Os dois indicadores devem ser analisados conjuntamente.

Um campus pode apresentar grande número de registros de evasão por possuir maior quantidade de matrículas. Outro campus pode possuir menor número absoluto de evasões e, simultaneamente, apresentar uma taxa proporcionalmente mais elevada.

> **As comparações entre atributos são descritivas.** Uma diferença entre homens e mulheres, grupos etários ou categorias de cor ou raça não demonstra que essas características causem a evasão.

## Limitações

- Os indicadores dependem da qualidade e da consistência dos dados registrados na PNP.
- A evasão corresponde à situação observada para determinada matrícula. Ela não demonstra abandono definitivo da educação.
- Uma mesma pessoa pode apresentar outras matrículas na Rede Federal ou continuar sua formação em outra instituição.
- Comparações temporais devem considerar alterações na composição da população, na oferta de cursos e no preenchimento das informações.
