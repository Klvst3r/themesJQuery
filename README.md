# temesJQuery
Creación de un generador de Temarios Reordenable.

El concepto General del presente proyecto de aplicación es la realización de un Temarios reordenable empleando las tecnologías de PHP, MySQL, AJAX y JQuery UI.

Server Windows at Work
AppServ 9.3.0 

    Apache 2.4.41
    PHP 7.3.10
    MySQL 8.0.17
    phpMyAdmin 4.9.1 Support TLS,SSL or https For 64bit only
    prepros 2021 -https://prepros.io/
    Bootstrap  v5.1.1 - https://getbootstrap.com/
    jQuery UI - jqueryui.com/sortable
    Bee Framework - https://github.com/Moxtrip69/Bee-Framework
    
    Dev Enviroment Win Link: https://www.appserv.org/en/ / LAMP - Linux
    

# Objetivo:
El objetivo es crear una herramienta para administrar de forma dinámica y facilitar la planeación de cursos o talleres, o alguna tematica que pueda emplearse en otras plaaformas dentro de una organización.

Se debe soportar el modo de trabajo drag and drop de elementos li que serán los temas en general o las lecciones a tratar, en cada lección se podran agregar un titulo y contenido que será opcional como el nombre del video que sera adjunto, documento o similar.

Se tendra entonces un campo id que será utilizado cuando:

1. Se editen los elementos de la lista de lecciones, 
2. 2. luego el titulo de la lección, 
3. 3. a continuación,
4. 4. el contenido de la lección.
5. y un selector múltiple para seleccionar el tipo de elementos de la lección (se tendra video, texto, enlace, descarga), y el boton de submit para guardar los cambios.

Será necesario un campo de status de cada lección, esto para determinar si ya fue creada o grabada, las opciones disponibles serán "pendinete" y "lista" para cuando se haya completado la producción de la lección.

Será posible borrar cada lección si es necesario o reordenar el temario a arrastrar y soltar, cada curso deberá tener un titulo general tentativo, un id y un folio solo para control administrativo.

A nivel temario se podrán borrar temarioscompletos y todas sus secciones incluidas, agregar nuevas, exportar cada temario a un documento . txt o .pdf tal vez.

Se usara el sistema de sesiones de usuario por defecto de Bee Framework, Bootstrap 5, jQuery y jQuery UI con sus elementos "sortable y accordion".
