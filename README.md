# SubeLibre — Plataforma de Almacenamiento de Archivos Multiformato

Aplicacion web que permite a los usuarios registrarse, subir y compartir archivos de distintos tipos (música, videos, imágenes y documentos). Incorpora un sistema de moderación, verificación de integridad y búsqueda avanzada.

## Funcionalidades principales

### Gestión de usuarios
- Registro y autenticación de usuarios con roles (user o admin).
- Perfil personal con listado de archivos subidos.
- Posibilidad de editar o eliminar archivos propios.

### Subida y organización de archivos
- Soporte para archivos de:
  - Música (.mp3)
  - Videos (.mp4)
  - Imágenes (.jpg, .png)
  - Documentos (.pdf, .docx, .txt)
- Almacenamiento físico estructurado por tipo y fecha.
- Verificación de integridad de archivos.
- Detección y rechazo de archivos maliciosos.
- Almacenamiento inicial en carpeta temporal hasta validación.

### Buscador avanzado
- Búsqueda de archivos por:
  - Nombre
  - Categoría
  - Tipo de archivo
  - Usuario que lo subió
- Resultados paginados y ordenables.

### Página de detalle por archivo
- Título y descripción personalizada (definida por el uploader).
- Metadatos visibles: tipo, tamaño, fecha, hash.
- Comentarios de otros usuarios.
- Enlace de descarga.

### Sistema de comentarios
- Usuarios registrados pueden comentar en archivos públicos.
- Moderación básica (eliminar comentarios ofensivos).
