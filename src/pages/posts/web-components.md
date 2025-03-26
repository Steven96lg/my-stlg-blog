---
layout: ../../layouts/PostsLayouts.astro
title: 'Sabes que son los web components?'
pubDate: 2022-07-01
description: 'Los frameworks y librerías como React, Vue y Angular nos ayudan a crear componentes web reutilizables, lo que supone una gran ventaja a la hora de escribir código. Sin embargo, existe una alternativa menos explorada pero igual de poderosa: los Web Components. Aprendamos un poco más sobre ellos.'
author: 'Astro Learner'
image:
    url: '../../../public/images/components.webp'
    alt: 'The Astro logo on a dark background with a pink glow.'
tags: ["astro", "blogging", "learning in public"]
---

Si bien existen frameworks y librerías como React, Vue o Angular (que son increíbles, sin duda, y muchas personas los prefieren), existe una forma de crear componentes totalmente independientes y reutilizables.

Estos son los Web Components. Una tecnología estándar en el desarrollo web que nos permiten crear elementos HTML personalizados y reutilizables totalmente independientes y encapsulados. ¿Qué significa que estos sean independientes y encapsulados?

Independientes: Cada componente opera de manera autónoma, sin depender del entorno en el que se ejecuta, y pueden funcionar fácilmente en cualquier aplicación web o framework. ¡Esto quiere decir que pueden implementarse en una aplicación hecha con React, Vue o Angular sin ningún tipo de problemas!

Encapsulados: Que sean encapsulados asegura que los estilos, la lógica y la estructura interna del componente no interfieran con el resto del documento HTML ni viceversa. Esto se logra mediante el uso del Shadow DOM.

- El CSS que se define dentro del componente no afectará otros elementos de la página.
- El JavaScript que se define dentro del componente, como las variables y funciones, está limitado a su contexto interno, evitando colisiones con el código global o de otros componentes.

Puedes pensar en un Web Component como una “caja negra” donde el diseño, funcionalidad y lógica están completamente controlados dentro del componente. Por ejemplo, si creas un botón personalizado con estilos específicos, esos estilos no modificarán los botones estándar de la página, ni los estilos de la página afectarán tu botón. Este diseño modular y aislado hace que los Web Components sean ideales para construir interfaces de usuario robustas y fáciles de mantener.

Ahora aunque podemos hacer Web Components de forma nativa con JavaScript en esta ocación exploraremos una libreria llamada lit-element que nos permite crearlos de manera rapida y sencilla.

para instalar lit-element vamos a ejecutar el siguiente comando.

```
npm install lit
```

```js
const init = "hello"
```