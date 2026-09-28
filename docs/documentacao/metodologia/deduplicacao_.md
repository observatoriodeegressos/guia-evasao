---
layout: default
title: "Deduplicação"
---

# {{ page.title }}

> **Regras distintas conforme a unidade de análise.** Por esse motivo, o total de evadidos apresentado pode variar entre módulos, indicadores e níveis de desagregação.

A Plataforma PNP Evadidos aplica regras distintas de deduplicação conforme a unidade de análise e a finalidade de cada indicador.

## Deduplicação por pessoa

Quando uma mesma pessoa possui registros de evasão em múltiplos cursos no período analisado, ela é contabilizada apenas uma vez nos indicadores cuja unidade de análise é a pessoa.

Preserva-se o curso de maior nível de ensino. Em caso de empate, preserva-se o registro de evasão mais recente.

## Deduplicação por curso

Cada combinação curso-pessoa é contabilizada uma única vez.

Essa regra permite que a mesma pessoa apareça em diferentes cursos quando possui registros de evasão em mais de um vínculo acadêmico.

Aplica-se às análises e visualizações desagregadas por curso.

## Deduplicação por vínculo empregatício

Quando o evadido possui múltiplos vínculos formais registrados na RAIS no período de referência, preserva-se o vínculo de maior remuneração para os indicadores que exigem um único vínculo representativo por pessoa.

Essa regra evita que uma pessoa com mais de um emprego formal seja contabilizada múltiplas vezes em indicadores cuja unidade de análise é o indivíduo.

## Deduplicação por trajetória acadêmica e produção científica

Quando o evadido possui múltiplos registros de pós-graduação, considera-se o título de maior nível de acordo com a regra estabelecida para o respectivo indicador.

Para produção científica, toda a produção elegível vinculada à pessoa é considerada.

Os registros de produção são deduplicados por normalização do título, com remoção de acentos e pontuação e truncamento do texto a 100 caracteres, conforme as regras adotadas no processo de integração dos dados.

## Síntese

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 30%; text-align: center">Unidade de análise</th>
      <th style="width: 70%; text-align: center">Regra aplicada</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Pessoa</strong></td><td>Uma ocorrência por pessoa. Preserva-se o curso de maior nível e, no empate, a evasão mais recente.</td></tr>
    <tr><td><strong>Curso</strong></td><td>Uma ocorrência por par curso-pessoa. A mesma pessoa pode aparecer em cursos distintos.</td></tr>
    <tr><td><strong>Vínculo empregatício</strong></td><td>Preserva-se o vínculo de maior remuneração quando o indicador exige um único vínculo por pessoa.</td></tr>
    <tr><td><strong>Trajetória acadêmica</strong></td><td>Considera-se o título de maior nível, conforme a regra do indicador.</td></tr>
    <tr><td><strong>Produção científica</strong></td><td>Toda a produção elegível é considerada, com deduplicação por normalização do título.</td></tr>
  </tbody>
</table>

> **As regras de deduplicação devem ser interpretadas em conjunto com a unidade de análise de cada indicador.** Uma pessoa pode contribuir uma única vez para um indicador populacional e aparecer em mais de uma categoria quando a análise considera vínculos acadêmicos distintos.
