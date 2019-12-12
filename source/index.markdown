---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Events

{% for member in site.data.events.events %}

**name**
### {{ member.name.text | escape }}

**link**
{{member.logo.original.url | escape}}

**html formatting**
<i>Test HTML</i>

**html link**

<img src="{{member.logo.original.url | escape}}" height="100">
This is a paragraph blah blah blah



{% endfor %}