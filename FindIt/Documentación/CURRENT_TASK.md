
# CURRENT_TASK.md

# 1. Tarea actual

Desarrollo del módulo de comunidades universitarias.

# 2. Objetivo

Desarrollar una sección dentro de la aplicación FindIt 
que permita visualizar las comunidades universitarias 
existentes en la plataforma, facilitando a los estudiantes 
identificar y acceder a la comunidad correspondiente a 
su universidad.

# 3. Alcance de la tarea

Se implementará:

- Pantalla principal de comunidades.
- Listado de las comunidades universitarias existentes.
- Visualización del nombre de cada universidad.
- Descripción breve de cada comunidad.
- Buscador de comunidades por nombre de universidad.
- Acceso a la comunidad correspondiente al estudiante.
- Interfaz organizada mediante tarjetas para presentar las comunidades.

# 4. Fuera del alcance

- Notificaciones de nuevas publicaciones.
- Gestión de administradores universitarios.
- Publicación de objetos encontrados dentro de este módulo.
- Chat privado entre estudiantes.

# 5. Reglas y restricciones

- Cada comunidad debe estar asociada a una universidad.
- Los estudiantes deben pertenecer a una universidad.
- Cada estudiante tendrá acceso únicamente a la comunidad
  de su universidad.
- Las comunidades deben mostrar información que permita 
  identificar a qué institución pertenecen.
- La información de las comunidades deberá obtenerse de 
  una fuente de datos.
- La interfaz debe adaptarse a dispositivos Android.

# 6. Criterios de aceptación

- Se muestra el listado de comunidades universitarias disponibles.
- Cada comunidad presenta el nombre de su universidad.
- El usuario puede buscar comunidades por nombre.
- El estudiante puede acceder a la comunidad correspondiente a su universidad.
- No se permite acceder al contenido de comunidades de otras universidades.
- La interfaz funciona correctamente en dispositivos Android.

# 7. Decisiones aprobadas

- La aplicación contará con comunidades independientes por universidad.
- Cada estudiante estará asociado a una universidad.
- Se utilizará .NET MAUI para desarrollar la aplicación Android.
- Se utilizará el patrón arquitectónico MVVM para organizar el código.

# 8. Decisiones pendientes

- Definir el diseño visual definitivo de las tarjetas de comunidades.
- Definir los datos adicionales que se mostrarán en cada comunidad.
- Definir el mecanismo para validar la pertenencia de un estudiante a una 
  universidad.
- Definir si se mostrará el número de integrantes de cada comunidad.


# 9. Estado

Pendiente de implementación.

# 10. Resultado esperado

Contar con un módulo de comunidades funcional que permita visualizar las
universidades registradas en FindIt, consultar su información y acceder a
la comunidad correspondiente, manteniendo separada la información de cada
institución.
