# Les dessins

## 2021
{% for drawings in site.collections %}
  {% assign name = collection.label %}
  <section>
    {% for drawing in site.[name] %}
    <article>
      <h2>{{ drawing.title }}</h2>
    </article>
    {% endfor %}
    
  </section>
{% endfor %}
