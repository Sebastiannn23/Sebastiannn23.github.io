---
title: home
permalink: /
---

## Este es el apartado de {{site.title}} De {{page.title}} 
<ul>
{% for page in site.pages %}
  <li>
    <a href="{{ page.url }}">{{ page.title }}</a>
  </li>
{% endfor %}
</ul>
 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

Puede utilizar el [editor en GitHub](https://github.com/Sebastiannn23) para mantener y obtener una vista previa del contenido de su sitio web en archivos Markdown

### Reducción

Markdown es una sintaxis ligera y fácil de usar para diseñar tu escritura. Incluye convenciones para

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image]({{ site.url }}/test/index.html)

[Link](url) and ![Image]({{ site.url }}/assets/img/logo-Jekyll.png)
```

![Image](/assets/img/logo-jekyll.png)

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/oscarnovillo/oscarnovillo.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
