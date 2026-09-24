---
layout: default
title: "Módulo 2 · Salários"
---

# {{ page.title }}

> **Remuneração dos vínculos formais identificados.** O módulo não mede a renda de todos os evadidos. Ele mede a remuneração registrada nos vínculos formais incluídos na análise.

O módulo Salários analisa a remuneração dos evadidos que possuem vínculo formal identificado na RAIS e informação salarial elegível para o cálculo.

## Organização do módulo

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 28%; text-align: center">Aba</th>
      <th style="width: 72%; text-align: center">Conteúdo</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Visão Geral</strong></td><td>Apresenta massa salarial e medidas de remuneração.</td></tr>
    <tr><td><strong>Salários por curso</strong></td><td>Apresenta os indicadores segundo características do curso associado à evasão.</td></tr>
    <tr><td><strong>Salários por atributos</strong></td><td>Apresenta os resultados segundo características sociodemográficas.</td></tr>
    <tr><td><strong>Salário Relativo</strong></td><td>Compara a remuneração observada no grupo analisado com a remuneração de referência utilizada para sua UF.</td></tr>
  </tbody>
</table>

## Formas de apresentação da distribuição salarial

O painel disponibiliza três formas de apresentação da distribuição salarial.

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 28%; text-align: center">Medida</th>
      <th style="width: 72%; text-align: center">O que representa</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Média aritmética</strong></td><td>Representa a média dos valores remuneratórios considerados.</td></tr>
    <tr><td><strong>Média logarítmica</strong></td><td>Utiliza a transformação logarítmica dos salários para reduzir a influência relativa de valores extremos.</td></tr>
    <tr><td><strong>Mediana</strong></td><td>Corresponde ao valor central da distribuição salarial.</td></tr>
  </tbody>
</table>

## Indicadores centrais

### 01 · Massa salarial · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Corresponde à soma das remunerações consideradas válidas para os evadidos ocupados.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Massa salarial = ∑ S<sub>i</sub><br><em>S<sub>i</sub></em>: valor remuneratório considerado para a observação <em>i</em>.</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e RAIS</td></tr>
  </tbody>
</table>

### 02 · Média salarial · *Quanto maior, melhor*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Apresenta a remuneração dos evadidos ocupados segundo a medida selecionada no painel.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Quanto maior, melhor.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Média aritmética: S̄ = ∑ S<sub>i</sub> / N<br>Média logarítmica: ln(S)‾ = ∑ ln(S<sub>i</sub>) / N<br>Mediana: Mediana(S) = P50</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e RAIS</td></tr>
  </tbody>
</table>

### 03 · Salário médio relativo · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Compara o salário médio observado entre os evadidos pertencentes ao grupo analisado com o salário médio de referência utilizado para a respectiva UF.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Salário relativo = Salário médio do grupo / Salário médio de referência da UF</td></tr>
    <tr><td><strong>Interpretação</strong></td><td>Valor igual a 1 representa igualdade entre as duas médias.<br>Valor superior a 1 indica remuneração média superior à referência.<br>Valor inferior a 1 indica remuneração média inferior à referência.</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e RAIS</td></tr>
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
    <tr><td>Visão Geral</td><td>Massa salarial por UF</td><td>Soma das remunerações segundo o recorte territorial selecionado.</td></tr>
    <tr><td>Visão Geral</td><td>Salário médio por UF</td><td>Remuneração média segundo UF, região ou instituição.</td></tr>
    <tr><td>Salários por curso</td><td>Salário médio por curso</td><td>Remuneração segundo o curso associado à evasão.</td></tr>
    <tr><td>Salários por curso</td><td>Salário médio por tipo de curso</td><td>Remuneração segundo a tipologia do curso.</td></tr>
    <tr><td>Salários por curso</td><td>Salário médio por turno</td><td>Remuneração segundo o turno do curso.</td></tr>
    <tr><td>Salários por atributos</td><td>Salário médio por sexo</td><td>Remuneração segundo sexo.</td></tr>
    <tr><td>Salários por atributos</td><td>Salário médio por faixa etária</td><td>Remuneração segundo grupos etários.</td></tr>
    <tr><td>Salários por atributos</td><td>Salário médio por natureza jurídica</td><td>Remuneração segundo a natureza jurídica ou administrativa do vínculo.</td></tr>
    <tr><td>Salários por atributos</td><td>Salário médio por cor ou raça</td><td>Remuneração segundo cor ou raça.</td></tr>
    <tr><td>Salários por atributos</td><td>Salário médio por ano de evasão</td><td>Remuneração segundo o ano da evasão.</td></tr>
    <tr><td>Salário Relativo</td><td>Salário relativo por sexo</td><td>Relação salarial segundo sexo.</td></tr>
    <tr><td>Salário Relativo</td><td>Salário relativo por tipo de curso</td><td>Relação salarial segundo o tipo de curso.</td></tr>
    <tr><td>Salário Relativo</td><td>Salário relativo entre recortes territoriais</td><td>Comparação da remuneração entre os recortes territoriais utilizados no painel.</td></tr>
    <tr><td>Salário Relativo</td><td>Salário relativo por setor econômico</td><td>Comparação segundo a atividade econômica do vínculo.</td></tr>
  </tbody>
</table>

**Fontes:** PNP, RAIS, CBO e CNAE.

## Limitações

- O módulo analisa somente os evadidos com vínculo formal e informação salarial válida.
- A ausência de informação salarial não significa ausência de renda.
- Os indicadores podem ser influenciados por jornada de trabalho, ocupação, setor econômico, localização, experiência profissional e outras características não controladas pelo painel.
- Os indicadores possuem finalidade descritiva.
