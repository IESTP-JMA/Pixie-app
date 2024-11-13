# Pasos a seguir para la creación del repositorio grupal.

1. Crear la carpeta del proyecto :

   ```mkdir PIXIE.app```

2. Acceder a la carpeta:

   ```cd PIXIE.app```

3. Inicializar repositorio :

   ```git init```
- Herramienta de diseño:
-  [Figma](https://www.figma.com/design/sm9mkMxDHL3XQN6boo32Tu/PIXIE-1.0?node-id=0-1&t=ZzZaygjJy3jvLcGN-1)
-  Modelo Entidad Relacion:
  +---------------+            +-------------------+
|   Usuario     |            |  Funcionalidad    |
+---------------+            +-------------------+
| PK ID_Usuario |<>--------<>| PK ID_Funcionalidad|
| Nombre        |            | Nombre            |
| Email         |            | Descripción       |
| Password      |            | Componente        |
+---------------+            +-------------------+

+---------------+            +-------------------+
| Administrador |            |     Feedback      |
+---------------+            +-------------------+
| PK ID_Admin   |<--------+  | PK ID_Feedback    |
| Nombre        |         |  | FK ID_Usuario     |
| Email         |         +--| Comentario        |
+---------------+            | Calificación      |
                             | Fecha             |
                             +-------------------+

+---------------+            +-------------------+
|    Imagen     |            |   Temporizador    |
+---------------+            +-------------------+
| PK ID_Imagen  |<>--------<>| PK ID_Temporizador|
| Ruta          |            | Duración          |
| Descripción   |            +-------------------+
+---------------+

+---------------+            +-------------------+
| Configuración |            |   Usuario         |
+---------------+            +-------------------+
| PK ID_Config  |<--------+  | PK ID_Usuario     |
| Nombre        |         |  | Nombre           |
| Estado        |         +--| Email            |
+---------------+            | Password         |
                             +-------------------+

