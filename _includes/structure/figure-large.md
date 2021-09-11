<figure class="figure">
<img src="{{page.large}}" alt="{{page.title}}" class="img-fluid"/>
<figcaption class="figure-caption mt-3">
  {% if page.record %}<a href="{{page.record}}">{%endif%}{%if page.accession %}Accession number: {{page.accession}}{% endif %}{% if page.record %}</a>{% endif %} {% if page.caption %}- {{ page.caption }}{% endif %}
</figcaption>
</figure>
