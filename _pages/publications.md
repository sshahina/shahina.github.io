
@@ -6,7 +6,7 @@ author_profile: true
---

{% if author.googlescholar %}
  {{ You can also find my articles on <u><a href="{% author.googlescholar %}">my Google Scholar profile</a>.</u> }}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
