# ¿Qué es Jupyter Book?

Jupyter Book es una herramienta para crear libros y documentos a partir de hardware informático. 
Es parte de las herramientas proporcionadas por el proyecto Jupyter. Este fue creado con **Jupyter 
Notebook**, por lo que hereda sus características, permitiendo a los lectores interactuar 
directamente con el contenido.

## ¿Como Funciona?

Integrado con el ecosistema de la UC3M a través de JupyterHub, puedes solicitar acceso a esta 
herramienta y crear contenido desde el terminal, desde cero o desde una plantilla editable.

## ¿Para qué lo puedo utilizar?

Puedes utilizar esta herramienta para escribir contenido con calidad de publicación en Markdown. 
Entre sus funcionalidades, se puede destacar el hecho de que permite crear material para el aula 
que contenga código, ecuaciones, figuras y referencias cruzadas de manera fácil.

````
Adicionalmente, permite generar outputs interactivos mediante la incrustación de notebooks y la 
descarga del material en distintos formatos.
````

```{note}
[Información Extraida de Aquí](https://www.uc3m.es/uc3mdigital/guia-herramientas/jupyter-book#:~:text=Jupyter%20Book%20es%20una%20herramienta,interactuar%20directamente%20con%20el%20contenido.).

```

### Formatos Más Utilizados

• **Texto en negrita/cursiva**: El texto en negrita se indica entre dos pares de asteriscos. De este modo **palabra** aparecerá como palabra. Por otro lado,
el texto en cursiva se indica entre dos asteriscos simples, es decir (palabra) aparecerá como *palabra*.

• **Listas**: Las listas en Markdown se realizan indicando un asterisco o un número seguido de un punto si se desean listas numeradas. Markdown organiza
automáticamente los items asignándoles el número correcto.

• **Inclusión de imágenes**: La sintaxis para incluir imágenes en Markdown es ![nombre alternativo](dirección de la imagen) en donde el nombre alternativo aparecerá en caso de que no se pueda cargar la imágen y la dirección puede referirse a una imagen local o un enlace en Internet.

• **Inclusión de código HTML**: El lenguaje Markdown es un subconjunto del lenguaje HTML y en donde se necesite un mayor control del formato, se puede incluir directamente en HTML.

• **Enlaces**: Las celdas de texto pueden contener enlaces, tanto a otras partes del documento, como a páginas en internet u otros archivos locales. Su sintaxis es
[texto](dirección del enlace)

````
Estas posibilidades permiten utilizar las celdas de texto de manera versátil documentando el código de otras celdas o, por ejemplo, explicando detalladamente algún
concepto teórico, del que después se puede presentar un ejercicio.
````