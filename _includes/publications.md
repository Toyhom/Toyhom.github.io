{% for pub in site.data.publications %}
- **{{ pub.title }}**  
  {{ pub.authors }}  
  {{ pub.venue }}{% if pub.links %} {% for link in pub.links %}[[{{ link.label }}]]({{ link.url }}){% unless forloop.last %} {% endunless %}{% endfor %}{% endif %}

{% endfor %}
