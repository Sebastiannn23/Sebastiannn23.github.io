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
        {% for notas in site.data.notas}
	<tr>
	   <th>{{notas.nombre}}</th>
	   <th>{{notas.notas}}</th>
	   <th>{{notas.sexo}}</th>
	  </tr>
	</table>
	</thead>
    {% endfor %}
