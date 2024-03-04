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
  ## Nombre {{ persona.nombre }} -  N° pokede {{ persona.edad }} - Genero {{ persona.sexo }} - Generacion {{ persona.generacion }}
{% endfor %}


---
title: personas
---
 ## personas

<h1>personas</h1>

<table>
	 <thead>
	  <tr>
	   <th>nombre</th>
	   <th>notas</th>
	   <th>sexo</th>
	  </tr>
	</thead>
        <body>
        {% for notas in site.data.notas}
	<tr>
	   <th>{{notas.nombre}}</th>
	   <th>{{notas.notas}}</th>
	   <th>{{notas.sexo}}</th>
	  </tr>
	{% endfor %}
	</table>
	</thead>
