# Guía de Estilo para la Interfaz Web de un Restaurante de Comida Rápida

Documento de referencia para diseñar una interfaz web orientada a la realización de pedidos online de forma rápida, intuitiva y atractiva para el usuario.

---

# 1. Identidad del Proyecto

| Aspecto | Descripción |
|--------|-------------|
| **Tipo de negocio** | Restaurante de comida rápida especializado en hamburguesas, patatas fritas y batidos. La experiencia se centra en la rapidez del servicio y la facilidad para realizar pedidos online o recogerlos en el local. |
| **Valores de la marca** | Rapidez, modernidad, energía y cercanía con el cliente, transmitiendo también una sensación de calidad en los productos. |
| **Público objetivo** | Personas jóvenes, familias y estudiantes u oficinistas que buscan comida rápida, accesible y fácil de pedir desde el móvil o el ordenador. |

---

# 2. Paleta de Colores

La combinación de colores busca estimular el apetito y transmitir dinamismo, utilizando tonos cálidos combinados con colores neutros que aportan contraste.

| Color | Código Hex | Uso y significado |
|------|-------------|-------------------|
| **Color principal (CTA)** | `#C42B2B` | Rojo intenso utilizado para destacar acciones importantes como botones de compra o llamadas a la acción. |
| **Color secundario** | `#FFC300` | Amarillo vibrante asociado a energía y dinamismo. Ideal para resaltar elementos importantes de la interfaz. |
| **Color base oscuro** | `#1E1E1E` | Negro carbón que aporta contraste, elegancia y modernidad. |
| **Fondo claro** | `#FFFFFF` o `#FAF7F5` | Tonos claros utilizados como fondo para mejorar la legibilidad y dar sensación de limpieza visual. |

### Uso del color

- En **fondos claros**, los colores principales serán el rojo y el amarillo para destacar elementos importantes.
- En **fondos oscuros**, el texto principal se mostrará en blanco o amarillo.
- Los **botones y llamadas a la acción** utilizarán preferentemente el rojo para captar la atención del usuario.

---

# 3. Tipografía

Se utilizarán fuentes **sans-serif modernas**, priorizando la claridad y la lectura rápida en dispositivos digitales.

| Elemento | Tipografía | Uso |
|----------|------------|-----|
| **H1** | Montserrat ExtraBold | Títulos principales de página. |
| **H2** | Montserrat Bold | Encabezados de secciones o subtítulos destacados. |
| **Texto general** | Roboto Regular / Medium | Descripciones de productos y contenido informativo. |

### Tamaños recomendados

| Dispositivo | H1 | H2 | Texto |
|-------------|----|----|-------|
| **Escritorio** | 48px | 32px | 16px |
| **Móvil** | 32px | 24px | 14px |

El peso **bold** en Roboto se utilizará especialmente para resaltar precios o elementos importantes del menú.

---

# 4. Iconos y Elementos Visuales

### Iconografía

- Iconos de estilo **relleno con líneas simples**.
- Esquinas ligeramente redondeadas para mantener una estética moderna.
- Uso para acciones comunes como **carrito, menú o ubicación**.

### Imágenes e ilustraciones

- Se priorizarán **fotografías reales de los productos** con alta calidad.
- Primeros planos de comida con colores vivos y atractivos.
- Las ilustraciones se utilizarán únicamente para representar servicios o beneficios, manteniendo un estilo minimalista.

Los iconos y elementos gráficos pueden incluir detalles en **amarillo y rojo** para mantener coherencia visual.

---

# 5. Botones y Llamadas a la Acción

Los botones deben destacar visualmente y facilitar la acción de compra.

| Tipo de botón | Diseño | Interacción |
|---------------|--------|-------------|
| **Principal** | Fondo rojo con texto blanco en negrita y bordes redondeados (4px). | Al pasar el cursor se oscurece ligeramente y aparece una sombra suave. |
| **Secundario** | Estilo contorno con borde rojo y fondo transparente o blanco. | Al hacer clic reduce ligeramente su tamaño para simular pulsación. |

El **botón del carrito de compra** permanecerá visible en todo momento, situado en la parte inferior derecha de la pantalla.

---

# 6. Estilo de Imágenes

### Prioridad visual
Las imágenes del catálogo utilizarán **fotografía real de los productos**.

### Tratamiento visual

- No se aplicarán filtros que alteren los colores naturales de los alimentos.
- Se potenciará la saturación y el contraste para aumentar el atractivo visual.
- Bordes redondeados de aproximadamente **8px** para un estilo moderno.

### Integración

- Las imágenes se mostrarán dentro de **cards** con fondo blanco.
- Las imágenes destacadas de portada podrán incluir una **superposición oscura** para mejorar la legibilidad del texto.

---

# 7. Espaciado y Layout

El diseño seguirá una estructura modular basada en un sistema de espaciado consistente.

### Escala de espaciado
Basada en múltiplos de **8px**:

`8px, 16px, 24px, 32px, 48px, 64px...`

### Márgenes y paddings

- Separación vertical entre secciones:  
  - **64px en escritorio**  
  - **40px en móvil**
- Padding interno de las cards: **16px**

### Contenedores

- Ancho máximo del contenedor principal: **1280px – 1440px**
- Las cards de producto se adaptarán a **3 o 4 columnas** en pantallas grandes.

La consistencia se mantendrá mediante **grids flexibles y media queries**.

---

# 8. Interacción y Usabilidad

| Elemento | Comportamiento |
|---------|----------------|
| **Mensaje de error** | Fondo rojo con texto blanco e icono de advertencia. Desaparece automáticamente tras unos segundos. |
| **Mensaje de éxito** | Fondo verde (`#4CAF50`) con icono de confirmación. También desaparece automáticamente. |
| **Navegación en escritorio** | Barra superior fija con botón destacado “Pide ahora”. |
| **Navegación en móvil** | Barra inferior con iconos principales como menú y carrito. |
| **Campos de formulario** | El borde se resalta en amarillo cuando el campo está activo. |
| **Menú móvil** | Menú desplegable lateral activado desde el icono de hamburguesa. |

---

# 9. Representación Visual de la Guía

La guía de estilos completa puede consultarse también en formato visual mediante un prototipo o diseño realizado en **Figma**, donde se muestran ejemplos de componentes, colores y tipografías aplicadas en la interfaz.