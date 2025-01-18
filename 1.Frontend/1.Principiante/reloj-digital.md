# Reloj Digital

## Descripción del Proyecto

Desarrolla un reloj digital en tiempo real utilizando **JavaScript**. El reloj debe mostrar la **hora** actual y actualizarse automáticamente cada segundo. Además, puedes agregar funcionalidades adicionales, como la **fecha actual** y la **zona horaria**.

## Requerimientos Principales

### 1. Funcionalidad del Reloj

- El reloj debe mostrar la **hora** en formato de 12 o 24 horas, dependiendo de la preferencia del usuario.
- El reloj debe actualizarse automáticamente cada segundo para mostrar la hora en tiempo real.

### 2. Mostrar la Fecha

- Junto con la hora, debe mostrarse la **fecha actual** en un formato legible (por ejemplo, "Viernes, 18 de Enero de 2025").
- La fecha debe actualizarse correctamente y reflejar el día actual.

### 3. Zona Horaria

- Muestra la **zona horaria** de la hora actual (por ejemplo, "GMT-3").
- Permite que el usuario pueda cambiar la zona horaria o detecte la zona horaria automáticamente si no se proporciona.

### 4. Interfaz de Usuario

- La interfaz debe ser clara y fácil de leer. Puedes usar un formato grande y destacado para la hora y la fecha.
- Asegúrate de que el reloj esté centrado en la página y que se vea bien en dispositivos móviles.

### 5. Funcionalidad Adicional (Opcional)

- Permitir que el usuario cambie entre el formato de 12 horas y 24 horas.
- Agregar un **estilo dinámico** que cambie el color de la hora dependiendo de la parte del día (por ejemplo, "verde" por la mañana, "amarillo" por la tarde, "rojo" por la noche).
- Permitir que el usuario vea la **hora en diferentes zonas horarias** del mundo, seleccionando otras ciudades o zonas horarias.

## Tecnologías Recomendadas

- **HTML**: Para la estructura básica de la página y la disposición del reloj.
- **CSS**: Para estilizar el reloj y hacerlo atractivo, con animaciones opcionales (por ejemplo, para actualizar la hora).
- **JavaScript**: Para actualizar la hora y la fecha en tiempo real, utilizando `setInterval()` para refrescar el reloj cada segundo.

## Estructura de Archivos

```bash
index.html # Archivo HTML para la estructura básica del reloj
style.css # Archivo CSS para personalizar la apariencia del reloj
script.js # Archivo JavaScript para manejar la actualización de la hora y la fecha
```

## Recomendaciones

- **Actualización en tiempo real**: Usa `setInterval()` en JavaScript para actualizar la hora cada segundo.
- **Formato de hora**: Utiliza el objeto `Date` de JavaScript para obtener la hora actual y formatearla correctamente.
- **Estilo responsivo**: Asegúrate de que el reloj sea visible y legible en pantallas de diferentes tamaños (móviles, tabletas, escritorios).

## Extensiones y Mejoras Posibles

1. **Añadir un reloj mundial**: Permitir al usuario ver la hora en diferentes zonas horarias alrededor del mundo.
2. **Alarma**: Agregar una funcionalidad para configurar alarmas a una hora específica.
3. **Temporizador**: Permitir al usuario usar un temporizador para medir intervalos de tiempo.
4. **Cambio de tema**: Permitir al usuario elegir entre diferentes temas visuales (modo oscuro, modo claro, colores personalizados).

¡Construye tu reloj digital y mejora tus habilidades con JavaScript! Este proyecto te ayudará a practicar con la manipulación de fechas y horas, y con la creación de aplicaciones en tiempo real.
