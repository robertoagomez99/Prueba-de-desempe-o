#  Explora el Mundo - Proyecto de portafolio


---

## 🎯 Objetivo del Proyecto

El objetivo de este sitio es mostrar una maqueta funcional y visualmente atractiva de un portafolio, con:

- Estructura semántica clara.
- Diseño moderno y adaptativo.
- Interacción visual mediante animaciones.
- Organización de contenido informativo y visual.

---

## 🛠️ Tecnologías Usadas

- **HTML5**
  - Etiquetas semánticas: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`.
  - Accesibilidad y estructura lógica.

- **CSS3**
  - Diseño responsivo con `Flexbox`, `Grid` y `Media Queries`.
  - `Transiciones` y `Animaciones` para efectos visuales.
  - `Background: linear-gradient` para mejorar el diseño visual.



---

## 📐 Estructura de Archivos

```
explora-el-mundo/
├── index.html        # Página principal con estructura semántica
├── style.css       # Estilos organizados por secciones y responsivo
└── README.md         # Documentación técnica del proyecto
```

---

## 🖥️ Contenido y Estructura

### 1. `header`
- Contiene el logotipo y el menú de navegación principal..

### 2. `main`
- Se divide en varias secciones semánticas:

#### 🔹 Sección `#inicio`
- Galería de imágenes de viajes.
- Implementación de `grid` responsivo con efecto `hover`.

#### 🔹 Sección `#proyecto`
- Imágenes con textos descriptivos y animación al pasar el cursor.

#### 🔹 Sección `#biografia`
- Artículos informativos del blog.
- Uso de `article` para estructurar contenido informativo.

#### 🔹 `aside`
- Formulario para suscripción de correo.
- Separación visual con fondo distinto y estilo de `card`.

### 3. `footer`
- Información de derechos y cierre del sitio.

---

## 🎨 Diseño Responsivo

- **`@media queries`** aplicados para diferentes anchos de pantalla:
  - Ajustes en la disposición del `main` (de columnas a una sola).
  - Menú de navegación adaptado a dispositivos móviles.
  - Galería y tarjetas ajustadas a pantallas pequeñas.

- **`auto-fit` y `minmax()`** usados para hacer que las imágenes se comporten de forma fluida y adaptable.

---

## ✨ Efectos Visuales

- **Animaciones CSS:**
  - `fadeIn`: aplicado a `header` y `footer` para suavizar la entrada.
  - `scaleIn`: animación de entrada para el logo.

- **Transiciones:**
  - Aplicadas a enlaces, botones e imágenes para lograr un efecto suave.
  - Hover sobre imágenes para resaltar.

---

## 🔎 Buenas Prácticas

- Código limpio y comentado.
- Separación de contenido y estilo.
- Nombres de clases descriptivos.
- Uso eficiente de `grid` y `flex` para estructura adaptable.
- Enlaces accesibles con buen contraste de color.

---

## 📱 Vista Responsiva

Puedes probar el diseño en distintos dispositivos usando las herramientas de inspección del navegador o redimensionando la ventana. Todo el contenido se ajusta correctamente sin perder funcionalidad ni diseño.

---

## 🧠 Sustentación Recomendada

Si vas a presentar este proyecto, puedes sustentar con los siguientes puntos:

- Justificación del uso de etiquetas semánticas (mejor accesibilidad y mantenimiento).
- Explicación de cómo se estructura el diseño para pantallas móviles.
- Justificar el uso de animaciones como mejora en experiencia del usuario.
- Hablar del uso de `auto-fit` y `minmax()` como solución escalable.
- Mencionar cómo separaste responsabilidades: HTML para contenido, CSS para diseño.

---

## 👤 Autor

Desarrollado por **[Tu Nombre Aquí]** como parte del módulo de **Desarrollo de Software** - 2025.

---


