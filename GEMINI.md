# Reglas y Estándares del Proyecto TECHNO WORLD

## 📌 Información General
- **Proyecto:** TECHNO WORLD Landing Page
- **Ruta Principal:** `C:\Users\Carlos Matute\Desktop\techno_world`
- **Enfoque de Diseño:** Minimalista de Tecnología, Línea Gráfica Corporativa, Mobile-First UI/UX.

---

## 🎨 Línea Gráfica y Paleta de Colores
- **Azul Primario:** `#3f5981` (Tonalidades corporativas `azul-50` a `azul-900`)
- **Acento Tecnológico:** `#4A90E2` / `#38bdf8` (Micro-glows, estados hover, enlaces activos)
- **Negro & Neutros Oscuros:** `#323232` (Superficie modo oscuro: `#080c14` / `#0f172a`)
- **Blanco & Neutros Claros:** `#e6e6e6` (Superficie modo claro: `#f8fafc` / `#ffffff`)
- **Tipografías:**
  - Encabezados: `Plus Jakarta Sans` (pesos 500, 600, 700, 800)
  - Textos: `Inter` (pesos 300, 400, 500, 600)
  - Logotipo: `ND Logos`

---

## 📱 Principios UI/UX para Móviles (Mobile-First)
1. **Navegación Táctil:**
   - Mantener la barra inferior rápida (`.mobile-bottom-bar`) para accesos rápidos con el pulgar.
   - Menú móvil tipo drawer con efecto difuminado (*glassmorphism*).
2. **Ergonomía de Formularios:**
   - Entradas de texto con tamaño mínimo de fuente de 16px para evitar auto-zoom en iOS.
3. **Flotante de WhatsApp:**
   - Posicionado estratégicamente para no solapar los controles de navegación.

---

## 🛠️ Tecnologías y Estructura
- **HTML5 Semántico** + **Tailwind CSS (CDN)** + **Vanilla CSS (`assets/css/estilos.css`)**
- **Ionicons (CDN)** para iconografía moderna.
- **Intersection Observer API** para animaciones Reveal suaves.
- **Canvas API** para la red interactiva de nodos en el Hero.
- **PHP** (`send.php`) para procesamiento de formulario de contacto.
