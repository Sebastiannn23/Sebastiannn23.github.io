---
title: Pokedex

---

# Pokedex


{% for member in site.members %}
  ## Nombre {{ member.name }} N pokedex {{ member.position }} Genero {{ persona.sexo }} Generacion {{ persona.generacion }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for persona in site.data.personas %}
  ## Nombre {{ persona.nombre }} N Pokedex {{ persona.edad }} Genero {{ persona.sexo }} Generacion {{ persona.generacion }}
{% endfor %}