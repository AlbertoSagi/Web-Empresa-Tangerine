# Web-Empresa-Tangerine

Aplicación desarrollada con Spring Boot Framework.
Este proyecto se basa en una web para una empresa dedicada al desarrollo web, donde ésta podrá mostrar todos sus proyectos y los clientes pueden contactar con ella.

La aplicación se va a dividir en tres grandes partes, a su vez subdivididas en otras partes:
   ● Base de Datos: Guardará de forma persistente los datos de la aplicación
   ● Parte REST API (puerto 5000): Comunicará con la Base de datos para obtener información y servir esa información a la parte Modelo-Vista-Controlador (MVC).
   ● Parte MVC (puerto 8080):
      ○ Controlador: Recibirá y procesará las peticiones de las diferentes páginas web
      ○ Modelo: consultará a la api la información necesaria
      ○ Vista: Generará las web correspondiente con la información solicitada. 
      
La web de Tangerine será capaz de:
   ● Mostrar una página Home agradable y comercial
   ● Mostrar los proyectos realizados e información sobre los mismos
   ● Mostrar los miembros de la empresa
   ● Permitir la gestión de proyectos
      ○ Añadir proyectos
      ○ Editar proyectos
      ○ Borrar proyectos
   ● Permitir la gestión de socios
      ○ Añadir socios
      ○ Editar socios
      ○ Borrar socios
   ● Permitir a los clientes contactar con la empresa a través de la página web
   ● Permitir al administrador ver los mensajes recibidos
   ● Permitir al administrador guardar las respuestas en la BBDD
   ● Permitir al administrador controlar los mensajes respondidos
