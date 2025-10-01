# 🏎️ Visualizador 3D de Llanta en WebGL

Un proyecto interactivo de gráficas por computadora que renderiza una llanta 3D en tiempo real usando WebGL y JavaScript puro, sin librerías externas de 3D. La escena presenta una llanta que orbita y rota sobre su propio eje, con una interfaz de usuario completa para controlar la visualización.

---

### ✨ Características Principales

* **Renderizado 3D:** La llanta (cilindro) se genera proceduralmente y se renderiza en tiempo real utilizando WebGL.
* **Animación Compleja:** La llanta no solo rota sobre su eje, sino que también sigue una trayectoria orbital, simulando un movimiento físico.
* **Texturizado Dinámico:** Permite cambiar las texturas del rin y del caucho en tiempo real, eligiendo entre 3 combinaciones diferentes para cada uno.
* **Cámara Interactiva:** Controles deslizantes (sliders) para manipular la cámara en 3D (ángulo horizontal, ángulo vertical y zoom).
* **Personalización de la Interfaz:**
    * Selector de paletas de color (Original, Rosado, Rojo) que cambia la apariencia de toda la interfaz.
    * El tema "Rosado" aplica una imagen de fondo personalizada.
    * El fondo tiene un sutil efecto de paralaje que reacciona al movimiento del mouse.

### 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura del proyecto.
* **CSS3:** Estilos avanzados para la interfaz, incluyendo variables CSS para el cambio de temas y un diseño responsivo.
* **JavaScript (WebGL):** Lógica principal para el renderizado 3D, manejo de shaders, matrices, animación y toda la interactividad de la página.
