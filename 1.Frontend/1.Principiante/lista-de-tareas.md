# Lista de Tareas (To-Do List)

## Descripción del Proyecto

Desarrolla una aplicación web sencilla que permita a los usuarios agregar, editar y eliminar tareas. Los datos de las tareas deben guardarse en el almacenamiento local (localStorage) del navegador para que persistan incluso cuando el usuario cierre la página o recargue la aplicación.

Este proyecto es ideal para principiantes que deseen practicar el uso de **HTML**, **CSS**, y **JavaScript**, además de trabajar con el almacenamiento local.

## Requerimientos Principales

### 1. Funcionalidad de la Lista de Tareas

- **Agregar Tareas**: Los usuarios deben poder agregar tareas a la lista.
- **Eliminar Tareas**: Los usuarios deben poder eliminar tareas que ya no necesitan.
- **Editar Tareas**: Los usuarios deben poder editar tareas existentes para modificar su descripción.
- **Guardar Tareas**: Las tareas deben guardarse en el almacenamiento local (localStorage) para que no se pierdan al recargar la página.

### 2. Interfaz de Usuario

- La aplicación debe mostrar las tareas en una lista.
- Debe haber un formulario o campo de texto para agregar nuevas tareas.
- Cada tarea debe tener botones para editar y eliminar.
- La lista debe actualizarse automáticamente cuando se agregue, edite o elimine una tarea.

### 3. Estilo y Diseño

- **CSS**: Para darle estilo a la lista, los botones de editar y eliminar, y otros elementos de la interfaz.
- La aplicación debe ser responsiva, adaptándose a diferentes tamaños de pantalla (PC, tablet, móvil).
- Se puede añadir un sistema de colores para diferenciar las tareas completadas de las pendientes.

## Tecnologías Recomendadas

- **HTML**: Para la estructura de la página y los formularios.
- **CSS**: Para la maquetación y el estilo visual de la aplicación.
- **JavaScript**: Para manejar las funcionalidades de agregar, editar, eliminar y guardar las tareas en **localStorage**.

## Estructura de Archivos

```bash
index.html # Archivo principal con la estructura de la aplicación
style.css # Archivo de estilos para personalizar la apariencia de la lista
script.js # Archivo JavaScript para la lógica de agregar, editar y eliminar tareasn
```

## Recomendaciones

- **Usa eventos**: Asegúrate de manejar eventos como `click` para agregar, editar y eliminar tareas.
- **Valida la entrada**: Verifica que el campo para agregar tareas no esté vacío antes de agregar una tarea.
- **Persistencia de datos**: Asegúrate de que las tareas se mantengan incluso después de recargar la página, usando **localStorage**.
- **Usabilidad**: Asegúrate de que la interfaz sea fácil de usar, especialmente para agregar y eliminar tareas rápidamente.

## Extensiones y Mejoras Posibles

1. **Marcar tareas como completadas**: Agregar un botón o checkbox para marcar las tareas completadas y que cambien de estilo visual.
2. **Filtrar tareas**: Permitir al usuario filtrar las tareas entre pendientes, completadas o todas.
3. **Ordenar tareas**: Implementar una funcionalidad para ordenar las tareas por fecha de creación o por prioridad.

¡Disfruta creando tu lista de tareas! Este proyecto te permitirá afianzar tus conocimientos en manipulación del DOM, eventos y almacenamiento local.
