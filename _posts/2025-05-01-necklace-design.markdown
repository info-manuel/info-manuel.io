---
layout: post
title:  "Diseño de colgante"
date:   2025-05-01 10:00:49 +0200
categories: jekyll update
---

# Projecto colgante

Quiero hacerle un regalo a mi mujer, un colgante con una moneda de oro, el problema está en que no quiero dañarla, por lo que agujerearla o soldarla a un aro no es una alternativa.

Este es el plan con el que creo que tendré éxito:

![Project Schema](/assets/images/necklace-design/Project-schema.png)

Mi diseño "en sucio" quedaría como muestro abajo, de esta forma la moneda podrá extraerse sin destruir el colgante:

![Full-Design-Constrained](/assets/images/necklace-design/Full-Design-Constrained.png)

*Dibujado en [ExcaliDraw](https://excalidraw.com)*

Este diseño consta de dos piezas necesarias para sujetar a la moneda, la primera pieza queda encajada dentro de la segunda, asegurada con un "pin" en la parte superior y con un remache en la parte inferior.

* Dimensiones de la moneda: Diametro 27mm, grosor 2.1mm.

Después de ver un par de tutoriales de [FreeCad](https://www.freecad.org), modelo mi diseño "en sucio":

![3d_parts](/assets/images/necklace-design/3d_parts.png)

Son observables dos grandes diferencias:

1. El pin de la parte superior es simplemente una extrusión en el eje vertical (Z).
2. No hay agujeros.

Ambas diferencias tienen como objetivo simplificar el molde sobre el cuál se volcará la fundición de metal.

Mi recomendación personal es la de simplificar al máximo uno de los ejes (X/Y/Z) antes de la función, además es bastante más sencillo hacer agujeros o lijar material sobrante que preparar un molde con geometría en los tres ejes:

![Geometria_Compleja](/assets/images/necklace-design/Geometria_Compleja.png)

No podemos hacer un molde de arena de un objeto como el mostrado arriba en *verde*.

.... Lets see how the 3d prints turns out (it will continue..) ...
