PROJETO DE LEI N. \_\_\_\_\_/{{ ano }}

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

{{ cargo }}{%p endif %}

{%p if anexos %}

{{ anexos.show(width=\'400px\') }}

{%p endif %}

{%p if anexos2 %}

{{ anexos2.show(width=\'400px\') }}

{%p endif %}

{%p if anexos3 %}

{{ anexos3.show(width=\'400px\') }}

{%p endif %}
