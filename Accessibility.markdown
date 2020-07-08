---
layout: page
title: Accessibility
---

# {{ page.title }}

Accessibility means not excluding anyone. 

We have a responsibility to make sure our online services (made up of websites, apps, forms and online documents) are accessible to everyone. 

<div class="previews">
  <div class="preview">
    <h2 class="sub-section-heading"><a href="/essex-service-transformation-playbook/Accessibility/Why-accessibility-is-important">Why accessibility is important</a></h2>
    <p>Includes information on the legal requirements and the benefits of creating accessible services</p>
  </div>
  <div class="preview">
    <h2 class="sub-section-heading"><a href="/essex-service-transformation-playbook/Content-style-guide/Content-guidelines">Content guidelines</a></h2>
    <p>Includes practical 'how to' guides and useful resources to help with writing and designing content</p>
  </div>
  <div class="preview">
    <h2 class="sub-section-heading"><a href="/essex-service-transformation-playbook/Accessibility/Making-your-service-accessible">Making your service accessible</a></h2>
    <p>Includes best practice guidance on how to make content accessible to users</p>
  </div>

  <div class="preview">
    <h2 class="sub-section-heading"><a href="/essex-service-transformation-playbook/Accessibility/Learn-about-accessiblity">Learn about accessibility</a></h2>
    <p>Accessibility training and information</p>
  </div>
</div>

{% assign ag = site.pages | where_exp: "item", "item.category contains 'Accessibility-guidelines' and item.live == true" %}
<div class="previews">
{% for item in ag %}
<div class="preview">
<h2 class="sub-section-heading"><a href="{{ item.url }}">
  {{ item.title }}
  </a>
</h2>
<p>{{ item.description }}</p>
</div>
{% endfor %}
</div>