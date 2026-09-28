---
layout: default
title: "Decisões metodológicas e seus vieses"
---

# {{ page.title }}

> **Toda decisão de tratamento dos dados produz consequências para a interpretação dos indicadores.** O quadro abaixo explicita as principais escolhas metodológicas, suas justificativas e os vieses ou limitações associados.

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th style="width: 18%; text-align: center">Decisão</th>
      <th style="width: 24%; text-align: center">O que foi decidido</th>
      <th style="width: 24%; text-align: center">Justificativa</th>
      <th style="width: 34%; text-align: center">Viés ou limitação introduzida</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Intervalo temporal entre a evasão e a RAIS de 2023</strong></td>
      <td>Utilizar a RAIS de 2023 para observar vínculos formais de estudantes classificados como evadidos na PNP até 2022.</td>
      <td>A separação temporal permite observar a inserção profissional após o registro de evasão e evita tratar resultados ocorridos antes da evasão como resultados posteriores.</td>
      <td>Pessoas que ingressam no mercado formal depois da janela observada não são identificadas nesse período. A limitação pode afetar grupos com inserção profissional mais tardia ou residentes em mercados de trabalho com menor oferta de emprego formal. Uma janela de acompanhamento mais longa pode identificar vínculos posteriores.</td>
    </tr>
    <tr>
      <td><strong>Curso de maior nível</strong></td>
      <td>Quando uma mesma pessoa possui registros de evasão em mais de um curso, preserva-se o curso de maior nível nos indicadores de empregabilidade, salários, empreendedorismo e produção científica. Em caso de empate, preserva-se a evasão mais recente.</td>
      <td>Evita a contagem múltipla da mesma pessoa e estabelece uma regra única e reproduzível para definir o vínculo acadêmico representativo.</td>
      <td>A regra reduz a participação dos cursos de menor nível nos recortes por curso dos indicadores calculados por pessoa. O curso selecionado não indica conclusão nem qualificação obtida. Essa seleção não se aplica à taxa de evasão nem à trajetória acadêmica.</td>
    </tr>
    <tr>
      <td><strong>Deduplicação por pessoa</strong></td>
      <td>Cada pessoa é contabilizada uma única vez, por CPF, nos indicadores de empregabilidade, salários, empreendedorismo e produção científica, independentemente da quantidade de registros de evasão existentes.</td>
      <td>Nesses indicadores, a população elegível é composta por pessoas únicas. Sem deduplicação, pessoas com múltiplos vínculos acadêmicos teriam maior peso no cálculo.</td>
      <td>Os totais de pessoas podem diferir dos totais de evasões utilizados na taxa de evasão e na trajetória acadêmica. Esses indicadores possuem unidades de análise diferentes. Nos indicadores calculados por pessoa, os recortes por curso utilizam exclusivamente o curso selecionado pela regra do maior nível.</td>
    </tr>
    <tr>
      <td><strong>Deduplicação por curso-pessoa</strong></td>
      <td>Na taxa de evasão e na trajetória acadêmica, contabiliza-se uma ocorrência de evasão por par curso-pessoa, preservando as evasões em cursos distintos.</td>
      <td>Permite analisar os diferentes vínculos acadêmicos da mesma pessoa sem contar repetidamente o mesmo par curso-pessoa.</td>
      <td>Uma pessoa com evasões em cursos distintos contribui com mais de uma ocorrência. Por isso, os resultados representam ocorrências de evasão e não pessoas únicas.</td>
    </tr>
    <tr>
      <td><strong>Cobertura do emprego restrita ao mercado formal identificado na RAIS</strong></td>
      <td>Utilizar a RAIS como fonte para identificar vínculos formais de trabalho.</td>
      <td>A RAIS permite identificar registros administrativos de emprego formal e vinculá-los aos estudantes da PNP por identificador individual.</td>
      <td>O indicador não mensura todo o universo de trabalho. Atividades informais, trabalho autônomo sem registro abrangido pelas bases utilizadas e outras formas de ocupação não observadas na RAIS ficam fora do indicador. Portanto, ausência de registro na RAIS deve ser interpretada como “sem vínculo formal identificado”, e não como desemprego ou ausência de atividade laboral. A limitação pode ser mais relevante em grupos e territórios com maior participação do trabalho informal.</td>
    </tr>
    <tr>
      <td><strong>Média geométrica como indicador salarial</strong></td>
      <td>Utilizar a média geométrica, calculada a partir da transformação logarítmica das remunerações, em vez da média aritmética para determinados indicadores salariais.</td>
      <td>A distribuição salarial costuma apresentar assimetria e valores elevados em sua cauda superior. A média geométrica reduz a influência de valores extremos sobre a medida de tendência central.</td>
      <td>A média geométrica tende a apresentar valor inferior à média aritmética quando existe dispersão salarial. Por isso, não representa a massa salarial média agregada e não deve ser interpretada como equivalente à remuneração média aritmética.</td>
    </tr>
  </tbody>
</table>

## Alcance interpretativo

Essas limitações não invalidam os indicadores. Elas definem seu alcance interpretativo.

A Plataforma PNP Evadidos apresenta resultados observados nas bases disponíveis e segundo as regras metodológicas adotadas. Os indicadores não permitem concluir, isoladamente, que a evasão causou determinado resultado profissional, salarial, empresarial, acadêmico ou científico.

> **Comparações entre instituições, cursos, regiões ou grupos de estudantes** também devem considerar diferenças de composição da população, cobertura das bases e tempo transcorrido desde a evasão.
