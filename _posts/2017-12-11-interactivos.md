---
layout: post
title: "Secciones cónicas"
author: "Román Contreras"
categories: journal
tags: [3d, ejemplo, conicas]
image:
  feature: inter-teaser.png
  teaser: inter-teaser.png
  credit: 
  creditlink: ""
---

En las siguientes gráficas interactivas, se puede explorar cómo cambia la solución de una ecuación cuadrática
$$aX^2+bXY+cY^2=K$$.

En la primera gráfica, la superficie roja es la gráfica de la función
$$f(X,Y)=X^2+tY^2 $$
donde el parámetro $$t$$ se puede controlar con el primer deslizador.
Por otro lado, la sufperficie azul es el plano $$\{Z=s\} $$ donde el parámetro  $$s$$ se puede controlar con el segundo deslizador.

De este modo, el conjunto de puntos que satisfacen la ecuación
$$X^2+tY^2=s$$
está representado por la intersección de ambas superficies.
<iframe scrolling="no" title="" src="{{site .baseurl}}/assets/interact.html" width="600px" height="600px" style="border:0px;"> </iframe>
Entre las cosas que se pueden apreciar es cómo cambia el comportamiento de la sulución al cambiar de signo el parámetro $$t$$, es decir,
como las soluciones pueden ser una elipse, una hipérbola, o dos rectas paralelas. También se puede observar el resultado de variar el par\ámetro $$s$$ y cómo para ciertas combinaciones de los parámetros, las dos superficies no se intersectan (es decir, ningún punto satisface la ecuación)

En la segunda gráfica, la superficie roja es la gráfica de la función
$$f(X,Y)=X^2+Y^2 +tXY$$
donde el parámetro $$t$$ se puede controlar con el primer deslizador.
Por otro lado, la sufperficie azul es el plano $$\{Z=s\} $$ donde el parámetro  $$s$$ se puede controlar con el segundo deslizador.

De este modo, el conjunto de puntos que satisfacen la ecuación
$$X^2+Y^2+tXY=s$$
está representado por la intersección de ambas superficies.

<iframe scrolling="no" title="" src="{{site .baseurl}}/assets/interact2.html" width="600px" height="600px" style="border:0px;"> </iframe>

Aquí se puede apreciar como afecta la presencia de un término cruzado no cero $$tXY$$

En caso de que la gráfica no se vea correctamente, aquí hay un enlace directo a ellas:
[Gráfica 1]({{site .baseurl}}/assets/interact.html)
[Gráfica 2]({{site .baseurl}}/assets/interact2.html)

