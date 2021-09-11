<figure class="figure">
<img src="{{page.large}}" alt="{{page.title}}" class="img-fluid"/>
<figcaption class="figure-caption mt-3">
  {% if page.record %}<a href="{{page.record}}">{%endif%}Accession number: {{page.accession}}{% if page.record %}</a>{% endif %} - {{ page.caption }}
</figcaption>
</figure>
