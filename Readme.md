# Pasos a seguir para la creación del repositorio grupal.

1. Crear la carpeta del proyecto :

   ```mkdir PIXIE.app```

2. Acceder a la carpeta:

   ```cd PIXIE.app```

3. Inicializar repositorio :

   ```git init```
- Herramienta de diseño:
-  [Figma](https://www.figma.com/design/sm9mkMxDHL3XQN6boo32Tu/PIXIE-1.0?node-id=0-1&t=ZzZaygjJy3jvLcGN-1)
-  [Modelo Entidad Relacion](https://dbdiagram.io/d/673406bae9daa85aca3db653)
-  Relaciones
### -Usuario - Funcionalidad: Un usuario puede tener acceso a múltiples funcionalidades, y cada funcionalidad puede ser utilizada por múltiples usuarios (Relación de muchos a muchos).
### -Administrador - Feedback: El administrador puede visualizar el feedback de los usuarios.
### -Usuario - Feedback: Un usuario puede dejar múltiples comentarios o calificaciones (Relación de uno a muchos).
### -Usuario - Imagen: Un usuario puede seleccionar múltiples imágenes y una imagen puede ser seleccionada por múltiples usuarios (Relación de muchos a muchos).
### -Usuario - Configuración: Un usuario puede activar o desactivar diferentes configuraciones en la aplicación (Relación de uno a muchos).

