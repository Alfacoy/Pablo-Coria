# Pablo Coria
### https://alfacoy.github.io/Pablo-Coria/

![Pablito](./app/image/readme-pablo.png)

Bueno! Fue la primera página que arme para alguien real de carne y hueso (?). Espero que le sirva mucho y pueda aumentar los Request de trabajos.

---

## El por que de las cosas

Pablo es albañil y herrero en estos momentos (2019), por lo que pensé en que lo mejor para él sería una **“Single Page”** donde se pueda mostrar sus trabajos más recientes y tener una opción de contacto para que la gente se comunique.

Para el nombre de dominio asumí que lo mejor sería colocar su propio nombre ya que quizas el dia de mañana se dedique a otra cosa y el dominio no coincida con la profesión. Además podríamos cambiar fácilmente el contenido de la web, pero recuperar la antigüedad de dicho dominio costaría mucho más.

Desarrolle la página  para ser consumida desde un celular basándome en  **Mobile First**. No coloque animaciones ni elementos que afecten la navegación del futuro cliente para evitar que se lleven una mala experiencia y den marcha atrás en el proceso . A partir de los 1300px para arriba es que coloque algunas animaciones simples.

Para los colores decidí usar un una escala de grises, no soy muy entendido del tema, pero sentí que le daban protagonismo a las imágenes y es justamente lo que buscaba. El verde que utilicé en el botón y la sección de contacto es el de la aplicación **“Whatsapp”**, con la intención de hacer un **call to action**. A este le agregue un gradiente en el eje horizontal para mejorar su aspecto a medida que aumenta el largo de pantalla.

* **$color-green**: #1BD741
* **$color-grey**: #222
* **$color-black**: #282C2F
* **$color-white**: #fff

Respecto al área donde detallo las experiencias que tuvo en ambos oficios (Albañilería y Herrería), siento que podría mejorar su diseño. Seguramente a futuro aprenda algo nuevo y pueda mejorarla. Por el momento cumple lo requerido de dar una introducción a sus experiencias.

La imágenes en la sección de “Mis Trabajos” están conectadas con **Instagram** con la intención de que ahí puedan encontrar más fotos. Considero que hoy en día Instagram como aplicación ayuda muchisimo a el pequeño y mediano emprendedor, ya que da la posibilidad de mostrar el trabajo que hacen y compartirlo fácilmente. Además al poder utilizarla desde el celular le da un impulso gigante para aquellas personas que no disponen de una computadora o simplemente no las entienden.

En el área de contacto decidí separar la información en tres filas:
* **Ubicación**:
  * Consideré que era más importante que el propio número de teléfono, por eso lo puse por encima, para así evitar            confusiones si llama alguien del interior del país o alguna localidad lejana. El nombre de dominio tiene la extensión “.com.ar” para tambien evitar trafico de otros paises. 
* **Whatsapp**:
  * El número de teléfono está enlazado con la aplicación de Whatsapp, de modo que al interactuar con este nos redirige a la app con un mensaje predeterminado para consultar cotización.
  * El número de teléfono está enlazado con la aplicación de Whatsapp, de modo que al interactuar con este nos redirige a la app con un mensaje predeterminado para consultar cotización.
* **Redes Sociales**:
  * En redes sociales simplemente es el enlace a su Instagram.

Respecto a los **Metadatos** sentí la necesidad de agregarle **Schema de tipo “persona”**. La intención está en proporcionarle la información rápido de Pablo al usuario de internet  que no tiene el interés de ingresar a la web. Por lo que su número de teléfono, profesión y ubicación ya están detalladas desde antes de ingresar a la página.

Para las personas que suelen **compartir** contenidos por **Twitter** o **Facebook** tambien los tome en cuenta, colocando las **Cards** y **Open Graph** de respectivas aplicaciones. Con esto evito que se muestre información que no es relevante al momento de compartir la web.

---

## Tecnologías usadas

* La página fue construida desde cero con HTML y CSS. 
* Utilicé Sass para hacer modular el código, no utilice mixins.
* Se utilizó también un poco de PostCSS para usar el plugin de autoprefixer.(1)
* Open Graph, Cards y Schema como Metadatos.

---

## ¿Piedras en el camino? Patealas

Si bien la página está terminada, el inicio fue caótico. Tuve problemas con los breakpoints en celular. Por suerte la gente de [@FrontEndCafe](https://twitter.com/FrontEndCafe) me facilitó esta web: [whatismyviewport](https://whatismyviewport.com/) para evitar tener esos inconvenientes.

(1) Para la animación de “Mis Trabajos” hubo un conflicto en las imágenes que al agrandarse se transparentaba los bordes y se veía la imagen inferior. Asumi que era un problema de los prefijos de navegadores por lo cual los coloque a todos, que no falte ni un maldito prefijo jaja, pero, no era la solución. Aún así, ahora están puestos todos, bien.

La solución al problema era que el z-index no responde a elementos con posiciones “static”, por lo que debí cambiar la posición de la imagen de static a relative. Esto fue aprendido de [@PabloHoc](https://twitter.com/pablohoc), también de [@FrontEndCafe](https://twitter.com/FrontEndCafe).

Commit del z-index  
https://github.com/Alfacoy/Pablo-Coria/commit/7e97f6690fad0bfce4fce295c3a6574cb7e8d35b

---

## Enlaces de utilidad

Visual Studio Code  
https://code.visualstudio.com/

Sass  
https://sass-lang.com/

PostCSS  
https://postcss.org/

What is my viewport    
https://whatismyviewport.com/

Twitter Cards  
https://developer.twitter.com/en/docs/tweets/optimize-with-cards/guides/getting-started

Open Graph  
https://developers.facebook.com/docs/sharing/webmasters#markup

Schema  
https://schema.org/Person



@[tecknchips](https://twitter.com/tecknchips) 2019
