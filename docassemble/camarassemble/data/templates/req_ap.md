REQUERIMENTO N. \_\_\_\_\_/{{ ano }}

Excelentíssimo Senhor

Vereador Leonardo Rodrigues da Silva Neto

Presidente da Câmara Municipal de

[ARAGUARI]{.ul}

Senhor Presidente,

{{ proponente }} que a este subscreve vem, respeitosamente, requerer,
ouvido o plenário na forma regimental, {{ assunto }}.

{%p if paragrafo1 != '' %}

{{ paragrafo1 }}

{%p endif %}

{%p if paragrafo2 != '' %}

{{ paragrafo2 }}

{%p endif %}

{%p if paragrafo3 != '' %}

{{ paragrafo3 }}

{%p endif %}

Nestes Termos, pede e espera deferimento.

Câmara Municipal de Araguari, Estado de Minas Gerais, sala das sessões
em {{ data }}.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

{{ autor }}

{{ cargo }} Proponente

ANTEPROJETO DE LEI N. \_\_\_\_\_/{{ ano }}

> "{{ ementa }}"

A Câmara Municipal de Araguari, Estado de Minas Gerais, aprova e eu,
Prefeito, sanciono a seguinte Lei:

> {%p for item in artigo %}

1.  {{ item }}.

> {%p endfor %}

2.  Revogadas as disposições em contrário, a presente Lei entra em vigor
    na data da sua publicação.

Câmara Municipal de Araguari, Estado de Minas Gerais, sala das sessões
em {{ data }}.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

{{ autor }}

{{ cargo }} Proponente

{%p if justificativa != '' %}

JUSTIFICATIVA:

{{ justificativa }}

Termos em que, atenciosamente, peço aprovação.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

{{ autor }}

{{ cargo }}

{%p endif %}

{%p if anexos %}

ANEXOS:

{%p endif %}

{%p if anexos %}

{{ anexos }}

{%p endif %}

{%p if anexos2 %}

{{ anexos2 }}

{%p endif %}

{%p if anexos3 %}

{{ anexos3 }}

{%p endif %}
