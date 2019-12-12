---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Events

{% for member in site.data.events.events %}

### {{ member.name.text | escape }}

<img src={{member.logo.original.url | escape }} height="100"/>


<img src=https://img.evbuc.com/https%3A%2F%2Fcdn.evbuc.com%2Fimages%2F83295571%2F150420679378%2F1%2Foriginal.20191203-030149?auto=compress&s=259e14f8c2502bae56836564cb42642e height="100"/>

test



{% endfor %}