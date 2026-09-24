---
layout: default
title: "Módulo 3 · Empreendedorismo"
---

# {{ page.title }}

> **Atividade empresarial formalizada.** O módulo representa empreendedorismo formal identificável administrativamente. Não cobre integralmente trabalho autônomo, atividade informal ou empreendimentos não registrados.

O módulo Empreendedorismo identifica a participação dos evadidos em atividades empresariais formalizadas nas bases administrativas utilizadas pela plataforma.

## Organização do módulo

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 32%; text-align: center">Aba</th>
      <th style="width: 68%; text-align: center">Conteúdo</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Visão Geral</strong></td><td>Apresenta os principais indicadores de empreendedorismo formal.</td></tr>
    <tr><td><strong>Empreendedorismo por curso</strong></td><td>Apresenta os resultados segundo características do curso associado à evasão.</td></tr>
    <tr><td><strong>Empreendedorismo por atributos</strong></td><td>Apresenta os resultados segundo características sociodemográficas.</td></tr>
    <tr><td><strong>Empresas Geral</strong></td><td>Apresenta informações sobre as empresas associadas aos evadidos.</td></tr>
    <tr><td><strong>Tipologia das Empresas</strong></td><td>Caracteriza os empreendimentos segundo atividade econômica, situação cadastral e porte.</td></tr>
  </tbody>
</table>

## Indicadores centrais

### 01 · Total de empreendedores · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza os evadidos identificados em vínculos empresariais considerados elegíveis pelas regras da plataforma.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>empreendedores</sub> = ∑ I(Empreendedor<sub>i</sub> = 1)</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e base CNPJ</td></tr>
  </tbody>
</table>

### 02 · Total de evadidos · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza os evadidos elegíveis para o cálculo da taxa de empreendedorismo.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>N<sub>evadidos</sub> = ∑ Evadidos</td></tr>
    <tr><td><strong>Fonte</strong></td><td>PNP</td></tr>
  </tbody>
</table>

### 03 · Taxa de empreendedorismo · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Indica a proporção de evadidos identificados em vínculos empresariais formais.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Taxa de empreendedorismo (%) = N<sub>empreendedores</sub> / N<sub>evadidos</sub> × 100</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e base CNPJ</td></tr>
  </tbody>
</table>

### 04 · Empresas identificadas · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Contabiliza os registros empresariais associados aos evadidos conforme as regras de vinculação adotadas no projeto.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Empresas = ∑ Empresas elegíveis</td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e base CNPJ</td></tr>
  </tbody>
</table>

### 05 · Capital social · *Descritivo*

<table border="1" cellspacing="0" cellpadding="5">
  <tbody>
    <tr><td style="width: 25%"><strong>Definição</strong></td><td>Apresenta o capital social declarado das empresas vinculadas aos evadidos.</td></tr>
    <tr><td><strong>Polaridade</strong></td><td>Descritivo.</td></tr>
    <tr><td><strong>Agregação máxima / mínima</strong></td><td>Rede Federal / Campus</td></tr>
    <tr><td><strong>Modelo matemático</strong></td><td>Capital social total = ∑ CapitalSocial<sub>j</sub></td></tr>
    <tr><td><strong>Fontes</strong></td><td>PNP e base CNPJ</td></tr>
  </tbody>
</table>

## Indicadores desagregados

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 28%; text-align: center">Aba</th>
      <th style="width: 28%; text-align: center">Indicador</th>
      <th style="width: 44%; text-align: center">Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Visão Geral</td><td>Total de empreendedores por campus</td><td>Quantidade de evadidos identificados como empreendedores segundo campus.</td></tr>
    <tr><td>Visão Geral</td><td>Taxa de empreendedorismo por UF</td><td>Percentual de empreendedores segundo UF, região ou instituição.</td></tr>
    <tr><td>Empreendedorismo por curso</td><td>Taxa por curso</td><td>Percentual de empreendedores segundo o curso associado à evasão.</td></tr>
    <tr><td>Empreendedorismo por curso</td><td>Taxa por tipo de curso</td><td>Percentual segundo a tipologia do curso.</td></tr>
    <tr><td>Empreendedorismo por curso</td><td>Taxa por turno</td><td>Percentual segundo o turno do curso.</td></tr>
    <tr><td>Empreendedorismo por atributos</td><td>Taxa por sexo</td><td>Percentual de empreendedores segundo sexo.</td></tr>
    <tr><td>Empreendedorismo por atributos</td><td>Taxa por faixa etária</td><td>Percentual segundo grupos etários.</td></tr>
    <tr><td>Empreendedorismo por atributos</td><td>Taxa por cor ou raça</td><td>Percentual segundo cor ou raça.</td></tr>
    <tr><td>Empreendedorismo por atributos</td><td>Taxa por ano de evasão</td><td>Percentual segundo o ano da evasão.</td></tr>
    <tr><td>Empresas Geral</td><td>Empresas por UF</td><td>Quantidade de empresas segundo localização.</td></tr>
    <tr><td>Empresas Geral</td><td>Localização e capital social</td><td>Relaciona localização, quantidade de empresas e capital social.</td></tr>
    <tr><td>Tipologia das Empresas</td><td>Empresas por atividade econômica</td><td>Distribuição segundo a CNAE.</td></tr>
    <tr><td>Tipologia das Empresas</td><td>Empresas por situação cadastral</td><td>Distribuição segundo a situação cadastral.</td></tr>
    <tr><td>Tipologia das Empresas</td><td>Empresas por porte</td><td>Distribuição segundo o porte empresarial.</td></tr>
  </tbody>
</table>

**Fontes:** PNP, base CNPJ e CNAE.

## Limitações

- A ausência de vínculo empresarial não comprova ausência de atividade empreendedora.
- O módulo não identifica integralmente atividades autônomas sem CNPJ, negócios informais, prestação eventual de serviços ou empreendimentos ainda não formalizados.
- Os resultados representam empreendedorismo formal identificado nas bases utilizadas.
