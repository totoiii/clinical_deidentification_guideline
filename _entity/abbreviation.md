---
layout: entry
title: "Abbreviation"
shortdef: "Procedimiento lingüístico de hacer más corta la morfología de ciertas palabras"
---

Se realiza empleando métodos como:

* Acortamiento: se elimina partes de las palabras al comienzo o al final (ej: "bicicleta" en bici, “autobús” en bus, o algunos más informales como poli por policlínico o refri por refrigerador).
* Abreviatura: consiste en la representación escrita de una palabra o grupo de palabras con solo una o varias de sus letras. Pueden ser de tipo personal (generadas para uso propio en escritura privada) o convencional (reconocidas y empleadas comúnmente). 
* Contracción: se eliminan las letras centrales de la palabra y se dejan solo las letras más representativas (por ejemplo, avda.).

Las abreviaciones incluyen los casos de siglas (creación de palabras a partir de cada letra inicial de los términos principales de una expresión compleja, como por ejemplo _ONU_ por Organización de las Naciones Unidas) y acrónimos (ciertas siglas que llegan a convertirse en vocablos comunes como _ovni_, _pyme_ y _sida_).

## Reglas positivas

* Etiquetar todas las abreviaciones tanto de tipo personal como convencional.

<div class="annotation-correct" markdown="1">
~~~ ann
Antec de repitencia …
T1 Abbreviation 0 5 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
Pcte persiste Psicótico …
T1 Abbreviation 0 4 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
… resulta normal ECG y Ecocardiograma …
T1 Abbreviation 17 20 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
Inicio de quetiapina 25mg
T1 Abbreviation 23 25 
~~~
</div>

* Etiquetar las abreviaciones de una letra o símbolo no estándar.

<div class="annotation-correct" markdown="1">
Correcto: se etiquetan tres abreviaciones
~~~ ann
TUS x OH
T1 Abbreviation 0 3 
T2 Abbreviation 4 5 
T3 Abbreviation 6 8 
~~~
</div>

<div class="annotation-correct" markdown="1">
Correcto: se etiquetan dos abreviaciones
~~~ ann
p hep normales
T1 Abbreviation 0 1 
T2 Abbreviation 2 5 
~~~
</div>

<div class="annotation-correct" markdown="1">
Correcto: se etiquetan dos abreviaciones
~~~ ann
MP  (+)
T1 Abbreviation 0 2 
T2 Abbreviation 5 6 
~~~
</div>

* Etiquetar todos los símbolos de palabras científicas o técnicas formados por letras convencionales que tienen validez internacional: Ag, Fe.

<div class="annotation-correct" markdown="1">
~~~ ann
Na 141, K 4.1, Cl 103
T1 Abbreviation 0 2 
T2 Abbreviation 8 9 
T3 Abbreviation 15 17 
~~~
</div>

* Etiquetar las abreviaciones numéricas ordinales conformadas por números y letras.

<div class="annotation-correct" markdown="1">
~~~ ann
10mo día de hospitalización
T1 Abbreviation 0 4 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
Lorazepam 1/2 ampolla  c/u
T1 Abbreviation 23 26 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
c/8 horas
T1 Abbreviation 0 2 
~~~
</div>

* Anotar los antecedentes gineco-obstetricos como abreviaturas sin incluir la numeración.

<div class="annotation-correct" markdown="1">
~~~ ann
G3 P1 A1
T1 Abbreviation 0 1 
T2 Abbreviation 3 4 
T3 Abbreviation 6 7 
~~~
</div>

* Anotar las pruebas de laboratorio que aparezcan de forma abreviada.

<div class="annotation-correct" markdown="1">
~~~ ann
SE ENCUENTRA HbA1C EN 17, TSH 7
T1 Abbreviation 13 18 
T2 Abbreviation 26 29 
~~~
</div>

* Anotar como abreviaciones los resultados de exámenes que indican positividad o negatividad.

<div class="annotation-correct" markdown="1">
~~~ ann
Paciente presenta VDRL +
T1 Abbreviation 18 22 
T2 Abbreviation 23 24 
~~~
</div>

## Reglas negativas

* NO incluir en la etiqueta los puntos, aunque sean puntos abreviativos. 

<div class="annotation-correct" markdown="1">
~~~ ann
Ac. Valproico
T1 Abbreviation 0 2 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
Dra. Juanita Pérez
T1 Abbreviation 0 3 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
… despertó a las 7:00 hrs. Plan: …
T1 Abbreviation 22 26 
~~~
</div>

* NO incluir en la etiqueta los paréntesis u otros separadores que no formen parte de la abreviación.

<div class="annotation-correct" markdown="1">
~~~ ann
Trastorno estrés post traumático complejo (DESNOS) 
T1 Abbreviation 43 49 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
Trastorno estrés post traumático complejo (DESNOS) 
T1 Abbreviation 42 50 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
FP/FR de …
T1 Abbreviation 0 2 
T2 Abbreviation 3 5 
~~~
</div>

* NO etiquetar abreviaciones correspondientes a nombres o apellidos.

<div class="annotation-incorrect" markdown="1">
~~~ ann
Dra. Juanita Pérez Z. 
T1 Abbreviation 19 21 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
Dra. J. Pérez. 
T1 Abbreviation 5 7 
~~~
</div>

* NO etiquetar las abreviaciones numéricas ordinales convencionales.

<div class="annotation-incorrect" markdown="1">
~~~ ann
8º día de hospitalización
T1 Abbreviation 0 2 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
Hoy se realizará 3ª sesión de … 
T1 Abbreviation 17 19 
~~~
</div>

<div class="annotation-incorrect" markdown="1">
~~~ ann
22º día de hospitalización
T1 Abbreviation 0 3 
~~~
</div>

* NO anotar como abreviaciones los nombres de las vertebras.

<div class="annotation-incorrect" markdown="1">
~~~ ann
con discopatia de L5-S1
T1 Abbreviation 18 20 
T2 Abbreviation 21 23 
~~~
</div>

* NO anotar como abreviaciones las evaluaciones semicuantitativas de exámenes.

<div class="annotation-incorrect" markdown="1">
~~~ ann
Signos de serosis: +++
T1 Abbreviation 19 22 
~~~
</div>

## Reglas multipalabra

* Anotar como una sola mención las abreviaciones que aparecen en el texto separados sólo por espacios o por guiones y que componen una entidad única.

<div class="annotation-correct" markdown="1">
~~~ ann
… diagnósticos de TAB I, y sospecha de …
T1 Abbreviation 18 23 
~~~
</div>

<div class="annotation-correct" markdown="1">
~~~ ann
…. ERC-IV recientemente pesquisado…. 
T1 Abbreviation 3 9 
~~~
</div>

* Anotar como una sola mención las abreviaciones que aparecen en el texto aparentemente compuestas por dos palabras pero que componen una entidad única.

<div class="annotation-correct" markdown="1">
~~~ ann
… bioquímico destacan hiperCa 10.5, HipoNa 132
T1 Abbreviation 22 29 
T2 Abbreviation 36 42 
~~~
</div>

<div class="annotation-correct" markdown="1">
Correcto: se anotan dos abreviaciones
~~~ ann
Paracetamol 500 mg xd
T1 Abbreviation 16 18 
T2 Abbreviation 19 21 
~~~
</div>
