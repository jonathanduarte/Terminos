---
layout: post
title:  "Differential Loading"
date:   2020-01-17
Author: Jonathan Duarte
shared-text: "Sabes lo que es Differential Loading? te invito a leer sobre el tema en:"
description: Differential Loading es un proceso mediante el cual el navegador elige entre Javascript moderno o heredado en función de sus propias capacidades, es decir se crean dos paquetes a compilar uno para los navegadores modernos que permiten ecma 2015 y un paquete para navegadores no tan nuevos que solo admiten la versión de ES5 de Javascript.
---


Differential Loading es un proceso mediante el cual el navegador elige entre Javascript moderno o heredado en función de sus propias capacidades, es decir se crean dos paquetes a compilar uno para los navegadores modernos que permiten ecma 2015 y un paquete para navegadores no tan nuevos que solo admiten la versión de ES5 de Javascript.

El navegador cargará automáticamente el paquete que le corresponda, gracias al soporte de los módulos de ES6 en los navegadores más nuevos, por lo que tendrán que cargar menos código y cargar una cantidad mucho menor de polyfills.

Pregunta. Ques es un polyfill?

Bueno, según nuestro amigos de [MDN][1] un polyfill es un fragmento de código (generalmente JavaScript) que se utiliza para proporcionar una funcionalidad moderna en navegadores antiguos que no lo admiten de forma nativa.

Por ejemplo, se podría usar un polyfill para imitar la funcionalidad de un elemento HTML Canvas en Microsoft Internet Explorer 7 usando un complemento de Silverlight, o un soporte mímico para las unidades rem CSS, o text-shadow, o lo que tu quieras.


__Eso es todo, por ahora...!__

[1]https://developer.mozilla.org/es/docs/Glossary/Polyfill