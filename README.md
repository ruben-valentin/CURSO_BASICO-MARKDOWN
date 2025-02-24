# CURSO_BASICO-MARKDOWN

# Curso Completo de Markdown - De Principiante a Experto

## Índice

1. [Introducción](#introducción)
2. [¿Qué es Markdown?](#qué-es-markdown)
3. [¿Por qué usar Markdown?](#por-qué-usar-markdown)
4. [Sintaxis básica](#sintaxis-básica)
   - [Encabezados](#encabezados)
   - [Énfasis (negrita e itálica)](#énfasis-negrita-e-itálica)
   - [Listas](#listas)
   - [Enlaces](#enlaces)
   - [Imágenes](#imágenes)
   - [Citas](#citas)
   - [Código](#código)
   - [Líneas horizontales](#líneas-horizontales)
5. [Sintaxis extendida](#sintaxis-extendida)
   - [Tablas](#tablas)
   - [Listas de tareas](#listas-de-tareas)
   - [Texto tachado](#texto-tachado)
   - [Emojis](#emojis)
   - [Notas al pie](#notas-al-pie)
   - [Definiciones](#definiciones)
6. [Formatos específicos de plataformas](#formatos-específicos-de-plataformas)
   - [GitHub Flavored Markdown](#github-flavored-markdown)
   - [GitLab Flavored Markdown](#gitlab-flavored-markdown)
   - [Discord Markdown](#discord-markdown)
   - [Reddit Markdown](#reddit-markdown)
7. [Markdown y HTML](#markdown-y-html)
8. [Herramientas para Markdown](#herramientas-para-markdown)
   - [Editores dedicados](#editores-dedicados)
   - [Extensiones para navegadores](#extensiones-para-navegadores)
   - [Plugins para editores de código](#plugins-para-editores-de-código)
   - [Convertidores](#convertidores)
9. [Mejores prácticas](#mejores-prácticas)
10. [Ejercicios prácticos](#ejercicios-prácticos)
11. [Recursos adicionales](#recursos-adicionales)
12. [Preguntas frecuentes](#preguntas-frecuentes)

---

## Introducción

¡Bienvenido al curso completo de Markdown! Si alguna vez has querido crear contenido bien formateado de manera sencilla y rápida, sin necesidad de aprender HTML o usar un procesador de texto complejo, entonces Markdown es para ti.

Este curso está diseñado para llevarte desde los conceptos más básicos hasta las técnicas avanzadas, con ejemplos prácticos que puedes seguir. Ya sea que quieras crear documentación técnica, escribir un blog, o simplemente formatear mensajes en plataformas como GitHub o Reddit, este curso te dará todas las herramientas que necesitas.

## ¿Qué es Markdown?

Markdown es un lenguaje de marcado ligero creado por John Gruber y Aaron Swartz en 2004. Su objetivo principal es permitir a las personas escribir texto con formato utilizando una sintaxis sencilla y fácil de leer, que luego puede convertirse a HTML.

![Creadores de Markdown](https://upload.wikimedia.org/wikipedia/commons/e/e6/Aaron_Swartz_profile.jpg "Aaron Swartz, uno de los creadores de Markdown")

El nombre "Markdown" es un juego de palabras con "markup" (marcado), sugiriendo que es una versión simplificada de los lenguajes de marcado tradicionales.

La filosofía detrás de Markdown es que el texto formateado debería ser legible sin que los símbolos de formato interfieran con la lectura, a diferencia de lo que ocurre con el HTML.

![Comparación entre Markdown y HTML](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Plain_Text_and_Markdown_Source_Code_%28Example%29.svg/1200px-Plain_Text_and_Markdown_Source_Code_%28Example%29.svg.png "Comparativa: texto plano vs Markdown")

## ¿Por qué usar Markdown?

Markdown ofrece numerosas ventajas que lo han convertido en una herramienta popular para escritores, desarrolladores y creadores de contenido:

1. **Simplicidad**: La sintaxis es intuitiva y fácil de aprender, sin necesidad de memorizar etiquetas complejas.

2. **Portabilidad**: Los archivos Markdown son archivos de texto plano (generalmente con extensión `.md` o `.markdown`) que pueden abrirse en cualquier editor de texto.

3. **Versatilidad**: Se utiliza en una amplia variedad de plataformas, desde sistemas de gestión de contenido hasta plataformas de desarrollo como GitHub.

4. **Conversión sencilla**: Puede convertirse fácilmente a HTML, PDF, DOCX y otros formatos.

5. **Enfoque en el contenido**: Te permite concentrarte en escribir en lugar de formatear.

6. **Control de versiones**: Al ser texto plano, funciona perfectamente con sistemas de control de versiones como Git.

7. **Independencia de plataforma**: No estás atado a un software específico o un sistema operativo concreto.

## Sintaxis básica

Vamos a aprender los elementos fundamentales de Markdown que te permitirán formatear la mayoría de tus documentos.

![Comparación de Markdown y su resultado HTML](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Markdown_flowchart.svg/825px-Markdown_flowchart.svg.png "Flujo de trabajo de Markdown")

### Encabezados

Los encabezados se crean usando el símbolo `#` seguido de un espacio. El número de símbolos `#` determina el nivel del encabezado:

```markdown
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

Que se visualiza así:

# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

También existe una sintaxis alternativa para los encabezados de nivel 1 y 2:

```markdown
Encabezado 1
===========

Encabezado 2
-----------
```

### Énfasis (negrita e itálica)

Para aplicar énfasis a tu texto, puedes usar asteriscos (`*`) o guiones bajos (`_`):

```markdown
*Este texto estará en itálica*
_Este texto también estará en itálica_

**Este texto estará en negrita**
__Este texto también estará en negrita__

***Este texto estará en negrita e itálica***
___Este texto también estará en negrita e itálica___
```

Que se visualiza así:

*Este texto estará en itálica*  
_Este texto también estará en itálica_

**Este texto estará en negrita**  
__Este texto también estará en negrita__

***Este texto estará en negrita e itálica***  
___Este texto también estará en negrita e itálica___

### Listas

Markdown soporta listas ordenadas y no ordenadas:

**Listas no ordenadas**

Puedes usar asteriscos (`*`), signos más (`+`) o guiones (`-`):

```markdown
* Elemento 1
* Elemento 2
  * Elemento 2.1
  * Elemento 2.2
* Elemento 3

+ Elemento 1
+ Elemento 2

- Elemento 1
- Elemento 2
```

Que se visualiza así:

* Elemento 1
* Elemento 2
  * Elemento 2.1
  * Elemento 2.2
* Elemento 3

**Listas ordenadas**

Utiliza números seguidos de un punto:

```markdown
1. Primer elemento
2. Segundo elemento
   1. Subelemento 2.1
   2. Subelemento 2.2
3. Tercer elemento
```

Que se visualiza así:

1. Primer elemento
2. Segundo elemento
   1. Subelemento 2.1
   2. Subelemento 2.2
3. Tercer elemento

Nota: Markdown es inteligente y mantendrá el orden correcto incluso si escribes números incorrectos:

```markdown
1. Primer elemento
1. Segundo elemento
1. Tercer elemento
```

Se mostrará como una lista ordenada correcta (1, 2, 3).

### Enlaces

Hay varias formas de crear enlaces en Markdown:

**Enlaces inline**:

```markdown
[Texto del enlace](https://www.ejemplo.com)

[Texto del enlace con título](https://www.ejemplo.com "Título que aparece al pasar el ratón")
```

Que se visualiza así:

[Texto del enlace](https://www.ejemplo.com)

[Texto del enlace con título](https://www.ejemplo.com "Título que aparece al pasar el ratón")

**Enlaces de referencia**:

```markdown
[Texto del enlace][referencia]

[otro enlace][otra-referencia]

[referencia]: https://www.ejemplo.com
[otra-referencia]: https://www.otroejemplo.com "Título opcional"
```

**Enlaces automáticos**:

```markdown
<https://www.ejemplo.com>

<correo@ejemplo.com>
```

Que se visualiza así:

<https://www.ejemplo.com>

<correo@ejemplo.com>

### Imágenes

La sintaxis para insertar imágenes es similar a la de los enlaces, pero con un signo de exclamación al principio:

```markdown
![Texto alternativo](https://ejemplo.com/imagen.jpg)

![Texto alternativo](https://ejemplo.com/imagen.jpg "Título opcional")
```

Esto se visualizaría así (ejemplo con una imagen real):

![Logo de Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "Logo de Markdown")

**Imágenes con referencia**:

```markdown
![Texto alternativo][id-imagen]

[id-imagen]: https://ejemplo.com/imagen.jpg "Título opcional"
```

**Imágenes con tamaño personalizado (usando HTML)**:

```markdown
<img src="https://ejemplo.com/imagen.jpg" width="200" height="150" alt="Texto alternativo">
```

**Imágenes como enlaces**:

También puedes hacer que una imagen funcione como un enlace:

```markdown
[![Texto alternativo](https://ejemplo.com/imagen.jpg)](https://sitio-destino.com)
```

Por ejemplo, esta imagen es un enlace que te llevaría a la página oficial de Markdown:

[![Logo de Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)](https://daringfireball.net/projects/markdown/)

### Citas

Para crear bloques de cita, utiliza el símbolo `>`:

```markdown
> Esta es una cita.
> 
> > Esta es una cita anidada.
> 
> Volvemos a la primera cita.
```

Que se visualiza así:

> Esta es una cita.
> 
> > Esta es una cita anidada.
> 
> Volvemos a la primera cita.

### Código

Para mostrar código hay dos opciones:

**Código inline**:

Utiliza comillas invertidas (`` ` ``) para marcar código dentro de un párrafo:

```markdown
Utiliza la función `print()` para mostrar un mensaje.
```

Que se visualiza así:

Utiliza la función `print()` para mostrar un mensaje.

![Ejemplo de código inline](https://i.imgur.com/ZjGLKFC.png "Código inline en Markdown")

**Bloques de código**:

Utiliza tres comillas invertidas (`` ``` ``) o indentar con cuatro espacios:

````markdown
```
def hello_world():
    print("Hello, World!")
```
````

O especificando el lenguaje para resaltado de sintaxis:

````markdown
```
def hello_world():
    print("Hello, World!")
```
````

Que se visualiza así:

```python
def hello_world():
    print("Hello, World!")
```

![Resaltado de sintaxis en bloques de código](https://i.imgur.com/gI3yDTZ.png "Resaltado de sintaxis para diferentes lenguajes")

### Líneas horizontales

Para crear una línea horizontal, puedes usar tres o más asteriscos, guiones o guiones bajos:

```markdown
***

---

___
```

Todas se visualizan como:

---

## Sintaxis extendida

Además de la sintaxis básica, muchas implementaciones de Markdown soportan características adicionales.

### Tablas

Puedes crear tablas usando barras verticales (`|`) y guiones (`-`):

```markdown
| Encabezado 1 | Encabezado 2 | Encabezado 3 |
|-------------|-------------|-------------|
| Celda 1,1   | Celda 1,2   | Celda 1,3   |
| Celda 2,1   | Celda 2,2   | Celda 2,3   |
```

Que se visualiza así:

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
|-------------|-------------|-------------|
| Celda 1,1   | Celda 1,2   | Celda 1,3   |
| Celda 2,1   | Celda 2,2   | Celda 2,3   |

**Alineación de columnas**:

Puedes alinear el texto en las columnas usando `:`:

```markdown
| Alineado izquierda | Centrado | Alineado derecha |
|:------------------|:--------:|-----------------:|
| Texto             | Texto    | Texto            |
```

Que se visualiza así:

| Alineado izquierda | Centrado | Alineado derecha |
|:------------------|:--------:|-----------------:|
| Texto             | Texto    | Texto            |

### Listas de tareas

Las listas de tareas te permiten crear listas de verificación:

```markdown
- [x] Tarea completada
- [ ] Tarea pendiente
- [ ] Otra tarea pendiente
```

Que se visualiza así:

- [x] Tarea completada
- [ ] Tarea pendiente
- [ ] Otra tarea pendiente

### Texto tachado

Para tachar texto, utiliza dos tildes (`~`) antes y después del texto:

```markdown
~~Este texto aparecerá tachado~~
```

Que se visualiza así:

~~Este texto aparecerá tachado~~

### Emojis

Muchas implementaciones de Markdown soportan emojis mediante códigos:

```markdown
:smile: :heart: :thumbsup:
```

En GitHub, esto se visualiza como: 😄 ❤️ 👍

### Notas al pie

Las notas al pie permiten añadir referencias:

```markdown
Aquí hay una nota al pie[^1].

[^1]: Esto es el contenido de la nota al pie.
```

### Definiciones

Algunas implementaciones permiten listas de definiciones:

```markdown
término
: definición

otro término
: otra definición
```

## Formatos específicos de plataformas

Distintas plataformas han ampliado Markdown con características adicionales.

### GitHub Flavored Markdown

GitHub utiliza su propia versión de Markdown con características como:

- Menciones a usuarios: `@usuario`
- Referencias a issues y pull requests: `#123`
- Emojis: `:smile:`
- Listas de tareas (como vimos anteriormente)
- Tablas
- Bloqueo de código con resaltado de sintaxis
- Autoenlaces para URLs

### GitLab Flavored Markdown

Similar a GitHub, pero con algunas diferencias:

- Resaltado de sintaxis mejorado
- Diagramas Mermaid y PlantUML integrados
- Math (ecuaciones matemáticas)

### Discord Markdown

Discord utiliza un subconjunto de Markdown:

```markdown
*itálica*
**negrita**
***negrita e itálica***
__subrayado__
~~tachado~~
`código`
```

Además, Discord tiene su propia sintaxis para spoilers:

```markdown
||Este es un spoiler||
```

### Reddit Markdown

Reddit también tiene su propia implementación:

```markdown
^texto ^superíndice
>!spoiler!<
```

## Markdown y HTML

Markdown fue diseñado para convertirse a HTML, y la mayoría de las implementaciones permiten mezclar HTML directamente en documentos Markdown:

```markdown
<div style="color: red;">
  Este texto será rojo en HTML.
</div>

Volvemos a **Markdown** normal.
```

Hay que tener en cuenta que algunas implementaciones pueden restringir qué etiquetas HTML están permitidas por razones de seguridad.

## Herramientas para Markdown

### Editores dedicados

Existen muchos editores específicos para Markdown:

- **Typora**: Editor WYSIWYG (lo que ves es lo que obtienes)
- **MarkText**: Editor de código abierto
- **Obsidian**: Perfecto para tomar notas y crear bases de conocimiento  
- **Zettlr**: Enfocado en académicos
- **iA Writer**: Minimalista, disponible para múltiples plataformas

### Extensiones para navegadores

- **Markdown Here**: Para escribir emails con formato
- **GhostText**: Para usar tu editor favorito en campos de texto web

### Plugins para editores de código

La mayoría de los editores de código tienen soporte para Markdown:

- **Visual Studio Code**: Vista previa integrada y extensiones
- **Sublime Text**: Paquetes para previsualización
- **Atom**: Soporte nativo y paquetes adicionales

### Convertidores

Herramientas para convertir Markdown a otros formatos:

- **Pandoc**: Convierte entre múltiples formatos
- **Markdown-PDF**: Convierte Markdown a PDF
- **Gitbook**: Para crear libros y documentación

## Mejores prácticas

Para usar Markdown de forma efectiva:

1. **Mantén la consistencia**: Decide un estilo (por ejemplo, usar asteriscos o guiones bajos para énfasis) y mantenlo en todo el documento.

2. **Usa líneas en blanco**: Separa párrafos y secciones con líneas en blanco para mejorar la legibilidad.

3. **Indenta correctamente**: Especialmente en listas anidadas y bloques de código.

4. **Nombra los enlaces**: Utiliza textos descriptivos para los enlaces en lugar de "haz clic aquí".

5. **Incluye textos alternativos**: Siempre añade textos alternativos a las imágenes para accesibilidad.

6. **Estructura con encabezados**: Utiliza una jerarquía lógica de encabezados para organizar tu contenido.

7. **Evita HTML innecesario**: Solo usa HTML cuando Markdown no puede hacer lo que necesitas.

8. **Usa listas adecuadamente**: Las listas ordenadas son para secuencias; las no ordenadas para elementos sin orden específico.

9. **Comentarios**: Algunas implementaciones permiten comentarios usando la sintaxis HTML: `<!-- Esto es un comentario -->`.

10. **Escapa los caracteres especiales**: Si quieres mostrar un carácter que normalmente se usa para formatear en Markdown, utiliza una barra invertida (`\`) antes:

    ```markdown
    \*Esto no está en itálica\*
    ```

## Ejercicios prácticos

Para practicar lo que has aprendido, intenta estos ejercicios:

### Ejercicio 1: Documento básico

Crea un documento que incluya:
- Un título principal
- Dos subtítulos
- Párrafos con texto en negrita e itálica
- Una lista ordenada
- Una lista no ordenada
- Un enlace a tu sitio web favorito

### Ejercicio 2: Tabla de comparación

Crea una tabla que compare tres productos o servicios, con al menos 5 características y alineación personalizada.

### Ejercicio 3: Guía de usuario

Crea una pequeña guía de usuario para una aplicación imaginaria, incluyendo:
- Instrucciones paso a paso (lista ordenada)
- Consejos útiles (citas)
- Ejemplos de código
- Una imagen (puedes usar una URL de placeholder)
- Una nota al pie con información adicional

### Ejercicio 4: Presentación técnica

Crea una presentación técnica con:
- Diferentes niveles de encabezados
- Bloques de código con sintaxis resaltada
- Tablas de datos
- Listas de verificación de características

## Recursos adicionales

Para seguir aprendiendo sobre Markdown:

- [Guía de Markdown de John Gruber](https://daringfireball.net/projects/markdown/)
- [Markdown Guide](https://www.markdownguide.org/)
- [Cheatsheet de GitHub](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Tutorial interactivo en CommonMark](https://commonmark.org/help/tutorial/)
- [Dillinger](https://dillinger.io/) - Editor en línea para practicar

## Preguntas frecuentes

**¿Cuál es la extensión de archivo para Markdown?**  
Normalmente `.md` o `.markdown`.

**¿Todos los sitios web interpretan Markdown de la misma manera?**  
No. Existen diferentes "sabores" de Markdown con variaciones en la sintaxis y características soportadas.

**¿Puedo convertir documentos de Markdown a Word o PDF?**  
Sí, herramientas como Pandoc pueden convertir Markdown a múltiples formatos.

**¿Puedo incluir imágenes locales en Markdown?**  
Sí, puedes usar rutas relativas: `![Texto alternativo](./imagenes/imagen.jpg)`

**¿Puede Markdown incluir tablas de contenido automáticas?**  
Algunas implementaciones lo soportan nativamente, otras requieren extensiones o plugins.

**¿Cómo puedo colorear el texto en Markdown?**  
Markdown puro no soporta colores de texto, pero puedes usar HTML inline: `<span style="color:red">texto rojo</span>`

**¿Markdown soporta ecuaciones matemáticas?**  
Depende de la implementación, muchas soportan LaTeX a través de extensiones como MathJax.

---

¡Felicidades! Has completado el curso completo de Markdown. Ahora tienes todas las herramientas para crear documentos bien formateados y legibles utilizando esta potente pero sencilla sintaxis de marcado. ¡Empieza a aplicar tus conocimientos en tus propios proyectos!
