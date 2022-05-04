## Picshar

Desarrollen el backend para un clon de Twitter + Instagram.

- La API debe satisfacer cada endpoint que está utilizando el frontend, de manera que el frontend funcione completamente. 
- La API debe crearse como repositorio en Github y debe ser "entregada" al profesor utilizando el enlace, donde se enviará unicamente el link al repositorio. 
- El proyecto se desarrolla en grupos de 3 personas, con fecha de entrega 1 de Junio.

Los endpoints a desarrollar incluyen, pero no están limitados a:

- [ ] Endpoint de login con usuario y contraseña
  - Debe generar un JWT de sesión
- [ ] Endpoint de login con JWT token
- [ ] Endpoint de registro de usuario


- [ ] Endpoint de informacion de usuario
  - No debe tener información privada del usuario (contraseña, fecha de cumpleaños)
  - Debe incluir el numero de publicaciones que el usuario ha dado me gusta, calculado on-demand
  - Debe incluir el numero de publicaciones que el usuario ha subido, calculado on-demand
  - Debe incluir el numero de seguidores del usuario, calculado on-demand
  - Debe incluir el numero de seguidos del usuario, calculado on-demand
- [ ] Endpoint de publicaciones que un usuario ha subido
  - Solo está permitido si el usuario esta siguiendo al usuario, a menos que sea el usuario mismo
- [ ] Endpoint de publicaciones que un usuario ha dado "me gusta"
  - Solo está permitido si el usuario permite ver sus "me gusta", a menos que sea el usuario mismo
- [ ] Endpoint de publicaciones que un usuario ha guardado
  - Solo está permitido para el usuario mismo
- [ ] Endpoint de usuarios seguidos por un usuario
  - Solo está permitido si el usuario esta siguiendo al usuario, a menos que sea el usuario mismo
- [ ] Endpoint de seguidores de un usuario
  - Solo está permitido si el usuario esta siguiendo al usuario, a menos que sea el usuario mismo

- [ ] Endpoint de solicitar seguir a un usuario
  - Solo permitido si el usuario ya no está siguiendo al usuario
- [ ] Endpoint de aceptar o rechazar solicitud de seguir
  - Solo está permitido si el usuario es el que recibe la solicitud


- [ ] Get timeline de un usuario
  - Debe ser paginada


- [ ] Endpoint de crear/subir publicacion
- [ ] Endpoint de informacion de publicacion


- [ ] Endpoint de dar me gusta a una publicación
- [ ] Endpoint de guardar una publicación
- [ ] Endpoint de comentar en una publicación

