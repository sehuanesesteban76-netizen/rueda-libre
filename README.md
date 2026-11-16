- Rueda Libre y Rueda Nocturna

Este proyecto tiene el sitio de Rueda Libre y una pagina para promocionar los recorridos nocturnos en bicicleta sobre Medllin. Desde el sitio principal se puede conocer la campaña, desde la campaña se puede volver al sitio y entrar a las opciones de reserva.

La carpeta nocturna guarda la landing de la campaña, la landing es una pagina hecha para mostrar un producto, servicio o campaña y ayudar a las personas a realizar una accion, or ejemplo en nuestro caso inscribirse a un recorrido.

- Enlaces de GitHub Pages

En GitHub Pages se publico contenido que esta en la rama main, estos son los enlaces del proyecto. 

- [Sitio principal de Rueda Libre](https://sehuanesesteban76-netizen.github.io/rueda-libre/)
- [Tarifas y rutas](https://sehuanesesteban76-netizen.github.io/rueda-libre/paginas/tarifas.html)
- [Reservas](https://sehuanesesteban76-netizen.github.io/rueda-libre/paginas/reservas.html)
- [Landing Rueda Nocturna](https://sehuanesesteban76-netizen.github.io/rueda-libre/nocturna/)
- [Kit de componentes](https://sehuanesesteban76-netizen.github.io/rueda-libre/nocturna/componentes.html)
- [Prototipo inicial](https://sehuanesesteban76-netizen.github.io/rueda-libre/nocturna/prototipo.html)

- Paginas del proyecto

- index.html: inicio del sitio Rueda Libre, se presenta el negocio y da acceso a sus secciones.
- paginas/tarifas.html: muestra las tarifas y recorridos.
- paginas/reservas.html: tiene el formulario para reservar una bicicleta.
- nocturna/index.html: presenta Rueda Nocturna, sus rutas, planes y formulario de inscripcion.
- nocturna/componentes.html: muestra los botones, una tarjeta, alertas y campos de formulario que forman el kit.
- nocturna/prototipo.html: primera idea visual de la campaña, creada antes de configurar Tailwind con la CLI.

- Tecnologias usadas

- HTML para organizar el contenido de las paginas.
- CSS propio para dar estilo al sitio principal.
- Tailwind CSS 3.4.17 para la landing y sus componentes.
- Tailwind CLI para crear el archivo nocturna/src/output.css.
- Google Fonts para el tipo de letras Montserrat y Open Sans.
- GitHub Pages para publicar el sitio.

La landing se adapta a distintos tamaños de pantalla. en celular muestra el contenido en una columna y en pantallas mas grandes organiza las rutas y los pasos en varias columnas tambien tiene colores para el modo claro y el modo oscuro.

Para generar de nuevo el CSS y que los cambos que hgas  se guarden, abre la terminal dentro de la carpeta nocturna y ejecuta:


.\node_modules\.bin\tailwindcss.cmd -i .\src\input.css -o .\src\output.css --minify


El archivo output.css se guarda en el repositorio porque GitHub Pages solo publica archivos. GitHub Pages no ejecuta Tailwind para crearlo.

- Mi decision entre Bootstrap y Tailwind

Para la landing recomiendaria seguir con Tailwind, esta decision la base en lo que pude construir y personalizar en este proyecto.

- Aprendizaje: con Bootstrap se usan estilos y componentes ya preparados. Con Tailwind se arma el diseño combinando clases pequeñas. Al principio tuve que acostumbrarme a escribir varias clases en el HTML, recomendaria boostrap psi se tiene que hacer el proyecto de manera rapida.
- Personalizacion: Tailwind me permitio usar los colores y las fuentes de Rueda Libre, cambiar el diseño por tamaño de pantalla y agregar modo oscuro.
- Tamaño final: el CSS minificado de la landing pesa 19.919 bytes. No medi los archivos con Bootstrap porque esa trabajo lo hice en otro proyecto.
- Uso: para este trabajo elegi Tailwind porque necesitaba ajustar la apariencia a la marca y me parecio mas divertido, y manejable hacerlo yo mismo. Bootstrap tambien sirve cuando se quieren usar componentes ya preparados y avanzar con una estructura conocida.

Esta recomendacion se basa en mi experiencia con la landing que hice con Tailwind.


- Como se construyo el proyecto

* Semana 1: HTML, accesibilidad y CSS: Esta semana construi la base del sitio Rueda Libre, trabaje con HTML, formularios y CSS.

    Durante esta semana construi la base del sitio Rueda Libre, aprendi a organizar paginas con HTML, usar etiquetas semanticas, crear formularios con validación y dar estilo con CSS tambien trabaje los colores de la marca y el espacio entre los elementos.

* Semana 2: Flexbox, Grid y diseño responsive

    Adapte el sitio para que se vea bien en celular, tablet y escritorio con flexbox ayudo alinee el encabezado, a Grid lo use para ordenar las tarjetas y otras partes del sitio.

    - Un encabezado que se acomoda: Flexbox.
    - La flota en cuadrícula: Grid.
    - Layout en dos dimensiones.

* Semana 3: Tailwind, campaña y entrega

Durante esta semana construi el proyecto Rueda Nocturna con Tailwind, cree sus componentes, la landing responsive, el modo oscuro, el formulario de inscripción y la sección de planes. Tambien conecte el proyecto con el sitio Rueda Libre, prepare la documentación y las capturas del proyecto.

    Pruebas y validacion
    
    - Revise la landing en modo dispositivo a 360, 768, 1024 y 1280 px.
    - Revise que en celular las rutas y los pasos se acomoden en una columna, y que en pantallas mayores aparezcan mas columnas.
    - Revise el modo claro y el modo oscuro.
    - Valide nocturna/index.html y paginas/reservas.html con W3C y pasaron la validación.
    - Falta revisar los enlaces de la version final en GitHub Pages despues de integrar los cambios en main.

    Capturas

    Estas imagenes muestran la landing en escritorio, en celular y en modo oscuro. La vista de celular y la vista oscura se capturaron a 360 px.

    Landing en escritorio: capturas/escritorio.jpeg
    Landing en celular: capturas/celular.jpeg
    Landing en modo oscuro: capturas/modo-oscuro.jpeg

- Tiempos de los retos con cronometro (Semana 3)

- MiniReto 9, formulario: 45 minutos.
- MiniReto 11, planes: 1 hora.


- Lo que aprendi

Aprendi a organizar una pagina con etiquetas HTML, crear estilos con CSS y Tailwind, y usar enlaces para conectar varias paginas. Tambien practique el diseño responsive, los formularios con validacion, los colores de marca, el modo oscuro, Grid y Flexbox.

Me intereso que hay que probar el sitio en varios tamaños de pantalla y con el teclado y tambien es importante volver a revisar los enlaces cuando se publica una version nueva.

## Pendiente para cerrar la entrega

- Integrar los cambios finales en main y revisar la version publicada en GitHub Pages.
- Abrir las paginas publicadas y probar sus enlaces.
- Ensayar la demo en menos de tres minutos.
- Anotar el tiempo que tomo la demo y el comentario real de un compañero.

- Autor

GitHub: [sehuanesesteban76-netizen](https://github.com/sehuanesesteban76-netizen)