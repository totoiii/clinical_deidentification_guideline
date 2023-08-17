---
layout: entry
title: "Date Part"
shortdef: "Etiqueta para un elemento o componentes de una fecha o referencia a una.
---

Una fecha se comprende como cualquier expresión que tenga un día, mes y año especifico. Date_part correspondería a una expresión que tenga una o varias componentes de una fecha. También pueden ser expresiones que hagan referencia a una fecha específica.

## Reglas positivas

* Etiquetar todas las .

<div class="annotation-correct" markdown="1">
~~~ ann
… secundario a prurito en piernas …
T1 Body_Part 26 33 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
… no se asocia a lesiones en la piel.
T1 Body_Part 32 36 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
… endometrio engrosado para edad.
T1 Body_Part 2 12 
~~~
</div>

<div class="annotation-correct" markdown="1">
Correcto: dos etiquetas separadas
~~~ ann
Cabeza y cuello: Normocraneo…
T1 Body_Part 0 6 
T2 Body_Part 9 15 
~~~
</div>

* Etiquetar las partes del cuerpo cuando forman parte de un problema médico.

<div class="annotation-correct" markdown="1">
~~~ ann
Hígado graso, 
T1 Body_Part 0 6 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
Cáncer de estómago
T1 Body_Part 10 18 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
Dolor en epigastrio
T1 Body_Part 9 19 
~~~
</div>

## Reglas negativas

* NO etiquetar los casos en los que la estructura corporal se utiliza en sentido figurado.

<div class="annotation-incorrect" markdown="1">
~~~ ann
… no tomar la solución en sus manos.
T1 Body_Part 30 35 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
… voces que escucha dentro de su cabeza.
T1 Body_Part 33 39 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
… “un click habia hecho en la cabeza”.
T1 Body_Part 30 36 
~~~
</div>

* No etiquetar las partes del cuerpo cuando son usados como adjetivos.

<div class="annotation-incorrect" markdown="1">
~~~ ann
Lupus cutáneo inactivo…
T1 Body_Part 6 13 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
Expresión facial fija y postura corporal fijas.
T1 Body_Part 10 16 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
Lesión corneal…
T1 Body_Part 7 14 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
Dolor abdominal ...
T1 Body_Part 6 15 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
Desdentamiento total bimaxilar
T1 Body_Part 21 30 
~~~
</div>

*  No anotar las parte del cuerpo que aparecen en abreviaturas aunque se puedan inferir.

<div class="annotation-incorrect" markdown="1">
Incorrecto: se anota como parte del cuerpo la abreviación de Núcleo Pulposo.
~~~ ann
Paciente consulta por antecedente de HNP
T1 Body_Part 38 40 
~~~
</div>

## Reglas multipalabra

* Etiquetar como una sola entidad las partes del cuerpo en las que se precisa su localización.

<div class="annotation-correct" markdown="1">
~~~ ann
Leiomiosarcoma muslo derecho con metástasis pulmonares
T1 Body_Part 15 28 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
Diverticulosis severa de colon sigmoides.
T1 Body_Part 25 40 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
… falanges distales 4 dedos mano izq.
T1 Body_Part 2 19 
T2 Body_Part 22 36 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
Extremidades inferiores: Pulsos pedios presentes… 
T1 Body_Part 0 23 
~~~
</div>
