---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
comments: true

---

<style>
.project-card {
  border: 1px solid #ccc;
  padding: 10px;
  margin: 10px 0;
}

.project-card h2 {
  margin-bottom: 5px;
}

.project-card a {
  display: inline-block;
  padding: 5px 10px;
  background-color: #007bff;
  color: #fff;
  text-decoration: none;
  border-radius: 3px;
}



</style>

<h2 class="post-list-heading">Reka Cipta Unggulan</h2>

{% for project in site.data.projects %}
  {% include projects.html %}
{% endfor %}