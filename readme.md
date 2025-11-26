##### Mapa del sitio
 La página web se organiza de la siguiente forma: 
 
```
mi_proyecto/
├── css/
│   └── estilos.css
├── src/
│   ├── index.html
│   └── contactos.html
└── README.md
```

La página principal es el index, tiene una barra de navegación que indica Inicio, Sobre nosotros, Recursos, Proyectos que referencian al index.html y sus respectivas secciones con nombres similares y Contactanos que referencia a contactos.html.

Además se tine los archivos estilos.css donde se personaliza algunos colores del root, además de utilizar bootstrap para mejor manejo de la estructuración de los márgenes, padings. También se utiliza los grid y flexbox propios de bootstrap para aprovechar la librería, a exepción de los botones 'Empieza ahora gratis' y 'Únete a la comunidad' de la seccion inicio que se implementa grid para organizar los botones, separarlos y adaptarlos con el media queries.