# Calculadora Simple

## Descripción del Proyecto

Construye una calculadora web que permita realizar operaciones básicas como **suma**, **resta**, **multiplicación** y **división**. La calculadora debe tener una interfaz sencilla con botones para cada número y operación. Este proyecto es ideal para practicar el uso de **HTML**, **CSS** y **JavaScript** para la creación de aplicaciones interactivas.

## Requerimientos Principales

### 1. Funcionalidad de la Calculadora

- **Operaciones básicas**: La calculadora debe ser capaz de realizar las siguientes operaciones:
  - **Suma** (+)
  - **Resta** (-)
  - **Multiplicación** (x)
  - **División** (÷)
- **Entrada de números**: Los usuarios deben poder ingresar números usando botones numéricos (0-9).
- **Pantalla**: La calculadora debe mostrar el número ingresado y el resultado de las operaciones en una pantalla o campo de texto.

### 2. Interfaz de Usuario

- **Botones**: Debe haber botones para cada número (0-9), operaciones (suma, resta, multiplicación, división), y un botón de igual (=) para obtener el resultado.
- **Pantalla**: Un área donde se mostrarán los números ingresados y el resultado de la operación.
- **Botón de Borrar**: Un botón para borrar la entrada actual (C o CE).

### 3. Lógica y Cálculos

- La calculadora debe realizar los cálculos cuando el usuario presiona el botón de igual.
- Debe manejar la **prioridad de las operaciones** (por ejemplo, multiplicación y división deben realizarse antes que suma y resta).

## Tecnologías Recomendadas

- **HTML**: Para la estructura de la página, los botones y la pantalla de la calculadora.
- **CSS**: Para el diseño de la interfaz, incluyendo botones, pantallas y disposición de los elementos.
- **JavaScript**: Para implementar la lógica de las operaciones matemáticas y la interacción con los botones.

## Estructura de Archivos

```bash
index.html # Archivo principal con la estructura de la calculadora
style.css # Archivo de estilos para personalizar la apariencia de la calculadora
script.js # Archivo JavaScript para manejar las operaciones matemáticas
```

## Recomendaciones

- **Eventos de clic**: Usa eventos `click` para cada botón, de modo que cuando el usuario presione un número o una operación, se agregue a la pantalla.
- **Operaciones matemáticas**: Utiliza la función `eval()` o crea una función personalizada para manejar las operaciones matemáticas y evitar errores.
- **Validación**: Asegúrate de manejar correctamente las entradas vacías o divisiones por cero.
- **Interactividad**: La calculadora debe ser fácil de usar, con botones grandes y una pantalla que se actualice inmediatamente cuando el usuario ingrese datos o realice una operación.

## Extensiones y Mejoras Posibles

1. **Operaciones avanzadas**: Agrega operaciones adicionales como **porcentaje**, **raíces cuadradas**, o **potencias**.
2. **Historial de operaciones**: Muestra un historial de las últimas operaciones realizadas.
3. **Estilo responsivo**: Asegúrate de que la calculadora se vea bien en dispositivos móviles y tablets.

¡Diviértete construyendo tu propia calculadora! Este proyecto es excelente para mejorar tus habilidades con el DOM, eventos y manipulación de datos en JavaScript.
