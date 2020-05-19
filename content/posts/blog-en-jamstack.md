---
title: Mi blog en JAMstack
date: 2020-05-19
published: true
tags: ['JAMstack']
canonical_url: true
description: "Hace poco un amigo me hablo de JAMstack como el futuro de la web, y resulta que JAMstack está entre nosotros hace ya un tiempo. Entonces quise experimentar un poco y decidí armar mi blog con este desarrollo."
---

Hace poco un amigo me hablo de JAMstack como el futuro de la web, y resulta que JAMstack está entre nosotros hace ya un tiempo. Entonces quise experimentar un poco y decidí armar mi blog con este desarrollo.

Comienzo diciendo que [JAMstack](//jamstack.org) no es una plataforma o una herramienta, sino una nueva manera de armar webs con contenido estático, que se caracterizan por mejor escalabilidad, mayor seguridad, mejor rendimiento y menor costo. JAM significa JavaScript, APIs, y Markup.

Como estoy reforzando mis conocimientos en javascript para luego meterme de lleno para aprender Vue.js, me pareció interesante probar esta nueva manera de crear sitios a ver qué tal me salía, y qué mejor que mi blog para arrancar.

### Buscando el framework

Investigando un poco todo el jamstack y teniendo en cuenta que quiero mi futuro en vue.js, encontre [Gridsome](//gridsome.org). Quizá no sea tan popular aún como Nuxt, pero su diseño me cautivó y me enamoré casi instantaneamente.
Gridsome es realmente muy rápido, genera los archivos necesarios y listos para deployar en minutos nomás. Como todo, tiene su curva de aprendizaje, pero es genial. Lo bueno que tiene, es que podes desarrollar de manera local, escribiendo los contenidos con markdown, pero incluso podes usar un *headless CMS* que lo vuelve más interesante.

### Headless CMS

Para este admin para crear contenido busqué varios, y la mayoría tienen su opción de pago. Por eso solo me quedé con dos: [Prismic](//prismic.io) y [Strapi](//strapi.io). El primero tiene su versión gratuita y muy completa, y el segundo es completamente *open-source* y lo podes correr de manera local sin inconvenientes.

Estoy usando un poco de los dos, porque estoy aprendiendo todo sobre la marcha y todavía estas cosas me cuestan un poco. Estas herramientas crean los JSON con los contenidos, se conectan con el framework y se arman tus archivos estáticos sin mayor esfuerzo.

### Deploy

Llegué a [Netlify](https://netlify.com/) la primera vez de casualidad, cuando quise deployar una página de status para [Cloudhost](//cloudhostla.com.ar). Armé la cuenta y empecé a jugar. Me di cuenta que de manera gratuita podés armar varios sitios, te brindan certificados SSL e incluso podés agregar tu propio dominio. Y como ya dije: costo cero. Lo único que haces es tirar el *build* de Gridsome y lo levanta en instantes.

### Conclusión

Este sistema de armado de webs es muy interesante, pero hay que tomarle bien la mano. Pero una vez que más o menos lo tenés, es muy conveniente, sobretodo si tenes webs a la que no les modificas el contenido tan seguido. Son rápidas, muchas veces gratis y seguras, ya que el contenido se consume de CDNs. Y si querés un blog como el que estoy armando, podes usar un *CMS sin cabeza*, conectar todo, pushearlo a Git y que se deploye de manera automática cada vez que haya un cambio.

Voy a ir subiendo el código del sitio a [Github](//github.com/calvonico) ni bien vaya mejorándolo.

Saludos, Nico.