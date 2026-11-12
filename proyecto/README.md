# Las películas de Tim Burton

## Autor

- **Nombre:** Roberto García García
- **Usuario de GitHub:** robeprom

## Tema elegido

Las películas más populares e importantes de Tim Burton.

## Por qué lo he elegido

He elegido este tema porque me gusta mucho el cine de Tim Burton y su
estilo gótico, que se reconoce nada más ver una imagen. Sus películas
mezclan terror, humor y personajes raros que acaban cayendo bien. Además,
da para mucho contenido: cada película tiene su año, su duración, sus
personajes y sus curiosidades, así que podré ampliar la web todo el curso.

## Palabra del día

metas

## ¿Qué he hecho en esta entrega?

En la clase de hoy he desarrollado el apartado del index.html, he buscado 
información acerca del tema elegido, he aprendido a usar etiquetas dentro 
de HTML y tambien he completado el apartado xml, he hecho los dos commit
y los he subido a github.

## UD3 · Estructura HTML

Cosas que le faltan a mi index.html según lo visto en clase:

1. **Metadatos en el head:** el `title` no sigue el formato «Inicio | Nombre
   del proyecto» y faltan las etiquetas `meta` description, keywords y author.
2. **Bloques div:** todo el contenido está suelto en el body, sin agrupar en
   bloques `div` ni comentarios que expliquen cada parte.
3. **Jerarquía de títulos:** solo hay un `h1` y un `h2`; faltan más `h2` y
   `h3` para organizar las secciones, además de cita, texto preformateado y
   pie de página con entidades.

### Validación W3C

He validado todas las páginas en validator.w3.org (Validate by File Upload).

| Página | Errores del validador | Cómo los corregí |
|---|---|---|
| index.html | 0 errores, 0 avisos | No tuvo errores. |
| peliculas.html | 0 errores, 0 avisos | No tuvo errores. |
| biografia.html | 0 errores, 0 avisos | No tuvo errores. |
| estilo.html | 0 errores, 0 avisos | No tuvo errores. |

### Qué he hecho en esta unidad

En esta unidad he movido mi proyecto a la carpeta proyecto/ y he mejorado el
index.html: he completado el head con title, description, keywords y author,
y he organizado el body en bloques div comentados con una jerarquía de
títulos sin saltos, una cita, una ficha en pre y entidades. Después he
diseñado el mapa del sitio y he creado tres páginas nuevas sobre Tim Burton
(películas, biografía y estilo), y las he validado todas en el W3C.

## Mapa del sitio

| Fichero | title | Qué contiene |
|---|---|---|
| index.html | Inicio \| Las películas de Tim Burton | Portada: presentación, lista de películas, mi opinión, ficha del director y enlaces. |
| peliculas.html | Películas \| Las películas de Tim Burton | Todas las películas de datos.xml (Corpse Bride, The Nightmare Before Christmas y Edward Scissorhands) con su argumento, estreno y duración. |
| biografia.html | Biografía \| Las películas de Tim Burton | Vida y carrera de Tim Burton: infancia en Burbank, sus años en Disney y sus grandes éxitos. |
| estilo.html | Estilo \| Las películas de Tim Burton | Rasgos de su cine gótico, sus colaboradores habituales y curiosidades. |
| contacto.html | Contacto \| Las películas de Tim Burton | Formulario de inscripción al maratón de cine de Tim Burton: datos personales, sesión, películas que quieres ver y comentarios. |

## UD5 · Tablas y formularios

En la página peliculas.html voy a poner una tabla con la filmografía de Tim Burton: el título de cada película, su año de estreno, su duración, si es de animación o de imagen real y quién hizo la música.
El formulario de la nueva página contacto.html servirá para que los visitantes se apunten en un maratón de cine de Tim Burton y elijan las películas que quieren ver.


### Método del formulario

Uso `method="post"` y no `get` porque con `post` los datos del formulario (nombre, correo, teléfono…) se envían dentro del cuerpo de la petición y no aparecen en la URL, mientras que con `get` quedarían a la vista en la barra del navegador y en el historial.

### Prueba con get

Al cambiar temporalmente el formulario a `method="get"` y pulsar «Enviar inscripción», la barra del navegador mostró esta URL (con datos de ejemplo):

```
file:///C:/Users/rober/Desktop/Instituto/Lenguaje_de_marcas/Proyecto_Integrado-LM-2026/proyecto/contacto.html?nombre=roberto+garcia&email=victor%40correo.com&telefono=600123456&sesion=tarde&peliculas=nightmare-before-christmas&peliculas=corpse-bride&favorita=corpse-bride&comentarios=holaaaaaaa&enviar=enviar#
```

Después volví a dejar el formulario con `method="post"`.

### Validación W3C

| Página | Errores del validador | Cómo los corregí |
|---|---|---|
| peliculas.html | 0 errores, 0 avisos | No tuvo errores. |
| contacto.html | 0 errores, 0 avisos | No tuvo errores. |

### Qué he hecho en esta unidad

En esta unidad he añadido a peliculas.html una tabla con la filmografía de Tim Burton, con caption, thead, tbody, tfoot, colgroup, celdas th con scope y un rowspan y un colspan. También he creado la página contacto.html con un formulario de inscripción a un maratón de cine, organizado en dos fieldset y con todos los tipos de control vistos en clase. Por último, la he enlazado desde index.html y el mapa del sitio y he validado las dos páginas en el W3C.