---
layout: post
title:  "Mejoremos el parque. ¡Y nuestra privacidad!"
date: 2019-01-08 10:00:00 -0300
categories: privacidad
permalink: /2019-01-11-salvemos-el-parque/
---

El 21 de Octubre del pasado 2018 fue el día escogido por las municipalidades de La Reina, Las Condes y Providencia para que sus habitantes votaran de manera vinculante para decidir sobre el futuro del Parque ~~intercomunal~~ Padre Hurtado. Por primera vez en Chile, un plebiscito de estas características se realizaría utilizando una plataforma de votación electrónica.
En palabras de los organizadores y de los responsables de la plataforma de votación, las elecciones culminaron en un rotundo éxito. Apenas cerrados los comicios y conocidos los resultados saldrían a celebrar el éxito del proceso y la gran participación en el mismo, todo sin mayores contratiempos durante la jornada. 77.812 votos fueron contabilizados[^1], situando inmediatamente esta consulta electrónica como la más masiva en la historia de nuestro país.
{: .text-justify}

Dada la popularidad de la consulta, durante los próximos días también oiríamos de detractores y voces más cautas sobre esta tecnología. El presidente del Servicio Electoral, declaró tajantemente que <q>En Chile no es necesario el voto electrónico</q>[^2]. Expertos en seguridad digital y derechos digitales también participarían en el debate, argumentando sobre los problemas intrínsecos de esta tecnología, de entre los más nombrados: la imposibilidad de asegurar el correcto funcionamiento del sistema; la posibilidad de que actores maliciosos cambien los resultados sin siquiera ser detectados, y la nula fiscalización que puede ejercer la ciudadanía sobre el proceso, muy distinto a lo que ocurre con nuestro actual sistema electoral[^3].
{: .text-justify}

Pero efectuar votaciones de este tipo no solo tiene problemas de seguridad o imposibilidad de verificar resultados por la ciudadanía. Estas consultas están generando delicada información sobre nosotros, quienes votamos o estuvimos habilitados para hacerlo. A modo de ejemplo, la figura 1 muestra el domicilio de las personas inscritas en Las Condes que votaron en el plebiscito entre las 10:53:30 y las 15:18:50.
{: .text-justify}

![]({{site.baseurl}}/assets/img/posts/2019-01-11-mapa-las-condes.png)
{: .image-center-90}
*Figura 1. Mapa de calor de los hogares de los votantes de “Mejoremos el Parque” en las condes en el intervalo indicado. Cada punto en el mapa es el hogar de un votante de Las Condes en el período señalado.*
{: .justify-width-90}

Cada punto en el mapa representa un voto recibido por el sistema. La ubicación de los puntos representa el hogar del votante y el momento en que el voto fue recibido por la plataforma de votación. Para cada persona que votó en esta consulta, se hizo pública: su identidad (rut, nombre); el identificador de la papeleta; y la dirección desde donde se efectuó el voto, esto es la IP del dispositivo utilizado para votar[^4].
{: .text-justify}

Esta elección permitió a los organizadores confeccionar una lista que contiene el nombre y rut de 77.812 personas, la hora en que cada una votó, y el lugar desde donde lo hicieron. Y lamentablemente no sabemos que van a hacer con ella, en la página de la votación no hay una línea dedicada a este tema. Lo que sí sabemos es que la protección de esta información fue deficiente. La lista estuvo publicada por días en la página de la votación, accesible para cualquier persona con una conexión a internet.
{: .text-justify}

El valor de esta información es reconocido, en el mundo hay empresas dedicadas a generar mantener y explotar este tipo de datos para construir perfiles políticos con el fin de influir en elecciones. Célebre es el caso de la británica *Cambridge Analytica*, conocida por recolectar información para elaborar sus perfiles a través de *Facebook* sin el consentimiento de los usuarios. Nada impide hoy que empresas de similares características estén vendiendo nuestros datos para influir la siguiente elección. Pero hoy no es *Facebook*, sino nuestras propias municipalidades quienes lo están haciendo posible.
{: .text-justify}

Este proceso es sólo otro ejemplo de cómo la privacidad y protección de nuestros datos está lejos de ser una prioridad para nuestras autoridades, proteger nuestros procesos democráticos podría ser un buen lugar para empezar a tomarnos este tema en serio.
{: .text-justify}
<br>


[^1]: https://bulletin.evoting.cl/parque/
[^2]: https://www.latercera.com/politica/noticia/presidente-del-servel-chile-no-necesario-voto-electronico/379900/
[^3]: https://radio.uchile.cl/2018/12/03/voto-electronico-todos-pierden/
[^4]:  El mapa no hace uso de esta dirección, sino del domicilio publicado por el Servel.

