# ROOMÉ — Plataforma 3D de Diseño de Interiores y Arquitectura

> *"Una experiencia interactiva de diseño de interiores en 3D sin límites creativos, permitiendo experimentar libremente con estilos, colores, patrones, materiales y tipologías de espacio."*

---

## 🚀 Despliegue en Vivo y Acceso
* **Repositorio oficial en GitHub:** [https://github.com/Isabelaneira/ROOME](https://github.com/Isabelaneira/ROOME)
* **Visualización local:** Abrir `index.html` en Google Chrome o cualquier navegador web moderno.
* **Servidor Node.js:** Compatible con Render, Vercel o ejecución local con `npm start`.

---

## 📋 Registro de Cambios y Nuevas Funcionalidades

### 1. 🏁 Motor de Patrones y Estampados Paramétrico
* **Biblioteca integrada de patrones:** Damero clásico, Rayas verticales y horizontales, Cuadrícula fina, Cuadros Tartán, Zigzag / Espiga (*Chevron*), Floral botánico, Baldosas hidráulicas artesanales, *Animal print* y Ondas retro años 70.
* **Control interactivo total:** Ajuste en tiempo real de escala de repetición ($1\times$ a $16\times$), rotación ($0^\circ$ a $360^\circ$), color primario y color de fondo.
* **Aplicación flexible:** Posibilidad de aplicar estampados a cualquier mueble seleccionado, a la pared de acento, a la pared posterior, al pavimento o a la alfombra.

### 2. 🎨 Sistema Cromático Ampliado & Selector HEX Libre
* **Selector universal:** Selector de color interactivo y campo de entrada de texto para cualquier código **HEX** (ej. `#D1286C`).
* **6 Familias organizadas:**
  * **Neutros:** Blanco puro, blanco cálido, crema, beige, gris piedra y negro carbón.
  * **Cálidos:** Terracota, ocre, mostaza, naranja caldera, teja y coral.
  * **Fríos:** Azul cielo, cobalto, marino profundo, salvia, menta y lavanda.
  * **Naturales:** Verde oliva, bosque, musgo, arena, arcilla y siena.
  * **Pasteles:** Rosa empolvado, lila, vainilla, celeste y melocotón.
  * **Intensos:** Azul Klein, verde esmeralda, fucsia y amarillo cúrcuma.

### 3. 🪵 Biblioteca de Materiales Nobles PBR
* **Maderas:** Roble claro, nogal oscuro, caoba y maderas lacadas.
* **Piedras:** Mármol blanco Carrara, mármol negro Marquina, mármol verde Alpi, travertino y terrazo veneciano.
* **Textiles:** Lino natural, terciopelo sedoso, bouclé cálido y cuero envejecido.
* **Metales:** Latón cepillado, cromo pulido, acero negro mate y cobre cálido.

### 4. 🏛️ Tipologías de Espacios y Plantillas
* **Salón Principal Contemporáneo:** Distribución de sala de estar completa con sofá bouclé, sillón escultórico y mesa orgánica.
* **Cocina con Isla & Comedor:** Isla central con encimera de piedra, estantería y taburetes.
* **Dormitorio Suite Principal:** Cama contemporánea, mesas auxiliares y espejo arqueado.
* **Terraza Mediterránea:** Comedor exterior, vegetación y olivo mediterráneo.
* **Cafetería Boutique / Comercial:** Barra de café, zona de mesas y luminarias de diseño.

### 5. ✨ Estilos de Diseño Predefinidos (1-Click Presets)
* **Japandi, Mediterráneo, Mid-Century Modern, Art Déco, Maximalista & Ecléctico, Memphis Design, Industrial Loft, Escandinavo Hygge y Minimalismo.**
* Modifican con un solo clic la luz ambiental, colores de muros y acabados.

### 6. 🌐 Compatibilidad y Servidor para Render
* Inclusión de `package.json` y `server.js` para despliegue como servicio web sin dependencias pesadas.
* Detección automática del puerto asignado por Render (`process.env.PORT`).

---

## 🛠️ Estructura del Proyecto
* **`index.html`**: Aplicación web interactiva 3D desarrollada con Three.js y WebGL.
* **`PROYECTO.md`**: Documento conceptual con los seis ejes estructurales de ROOMÉ.
* **`ROOMÉ_ASSETS.blend`**: Biblioteca de modelos 3D y habitación de prueba modelada en Blender.
* **`server.js`**: Servidor Node.js ligero para servir la aplicación en internet.
* **`package.json`**: Configuración de ejecución y scripts para Render y Node.js.
* **`.gitignore`**: Configuración de exclusión para archivos pesados y sensibles.
