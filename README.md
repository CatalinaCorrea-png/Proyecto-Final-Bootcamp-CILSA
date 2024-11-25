# Proyecto Final Bootcamp CILSA
Aplicación web para gestionar una lista de tareas (SPA). Los usuarios podrán agregar nuevas tareas, marcar tareas como completadas, editar tareas existentes y eliminar tareas. <br>
La aplicación cuenta con una interfaz intuitiva y fácil de usar.
Los usuarios deben registrarse e iniciar sesión para comenzar a crear tareas. 
Cada usuario tiene sus propias tareas.
## ARQUITECTURA DE LA APLICACIÓN
### FRONT-END
Front-end de una sola página dinámico con tecnología React.js, utilizando React Router para navegar entre paginas o componentes sin actualizar el navegador e implementando rutas privadas.
### BACK-END
Back-end con tecnología Node.js y Express.js, que maneja las solicitudes HTTP de los formularios de Register, Login y de Tareas, y se conecta con la base de datos.
### BASE DE DATOS
Base de datos relacional con motor MySQL. Se tienen dos tablas, la tabla de USERS y la tabla de TAREAS. Tienen una cardinalidad 1:M, donde cada user puede tener varias tareas.
## RESUMEN DEL PROYECTO (PAGINAS)
### Landing Page
La primer pagina que el usuario ve es una bienvenida con el nombre de la web y una explicación concreta de su función.
### Formularios
Un registro y un Inicio de Sesión para crear y utilizar una cuenta en la que el usuario tendrá sus tareas personales.
Se valida la integridad de los datos tanto en el front como en el back.
### Pagina Principal / CRUD
Un formulario simple que permite agregar nuevas tareas a la lista.
Se puede editar una tarea, eliminarla o marcar como completada.
## EQUIPO
#### Catalina Yazmín Correa (Desarrolladora)
LinkedIn: https://www.linkedin.com/in/catalina-yazm%C3%ADn-correa-576037211/ <br> Github: https://github.com/CatalinaCorrea-png 
#### Alejandro  Piris (Desarrollador)
LinkedIn: https://www.linkedin.com/in/alejandro-piris-4aa20520b/  <br> Github: https://github.com/AlePiris 
#### Mariano Germán Infante Contreras (Desarrollador)
LinkedIn: https://www.linkedin.com/in/mariano-infante/ <br>
Github: https://github.com/MGIC12 