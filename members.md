---
title: Pokedex

---

# Pokedex


{% for member in site.members %}
  ## Nombre {{ member.name }} -  N° pokede {{ member.position }} - {{ persona.sexo }} - {{ persona.generacion }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for persona in site.data.personas %}
  ## Nombre {{ persona.nombre }} -  N° pokede {{ persona.edad }} - {{ persona.sexo }} - {{ persona.generacion }}
{% endfor %}