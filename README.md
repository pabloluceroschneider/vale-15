# 🎉 Invitación 15 Años - Valentina

Una elegante página web de invitación para los 15 años de Valentina, diseñada con HTML, CSS y JavaScript vanilla.

## ✨ Características

- 🎨 **Diseño responsive** - Se adapta perfectamente a móviles y desktop
- ⏰ **Cuenta regresiva en tiempo real** hasta la fecha del evento
- 🌟 **Efectos parallax** suaves en cada sección
- 🧭 **Navegación sticky** con enlaces a cada sección
- 💕 **Animaciones de corazones** flotantes
- 📍 **Integración con Google Maps** para la ubicación
- 📱 **Enlaces directos** a WhatsApp y Google Forms

## 🚀 Despliegue en GitHub Pages

### Paso 1: Configurar el repositorio

```bash
# Clonar o crear tu repositorio
git clone https://github.com/TU-USUARIO/invitacion-15-anos-valentina.git
cd invitacion-15-anos-valentina

# Instalar dependencias
npm install
```

### Paso 2: Configurar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Settings → Pages
3. Source: "Deploy from a branch"
4. Branch: `gh-pages`
5. Folder: `/ (root)`

### Paso 3: Desplegar

```bash
# Desplegar a GitHub Pages
npm run deploy
```

### Comandos disponibles

```bash
# Servir localmente para desarrollo
npm start

# Servir en puerto específico
npm run serve

# Desplegar a GitHub Pages
npm run deploy
```

## 📝 Personalización

### Cambiar información del evento

Edita las siguientes secciones en `index.html`:

1. **Fecha y hora**: Línea donde aparece `2025-08-29T21:00:00`
2. **Ubicación**: Actualiza el enlace de Google Maps
3. **Precios**: Cambia los valores `$0000`
4. **Enlaces**:
   - WhatsApp: Actualiza el número de teléfono
   - Google Forms: Cambia la URL del formulario

### Cambiar imágenes de fondo

Las imágenes están en las clases CSS `.section-1 .parallax-bg` hasta `.section-5 .parallax-bg`.
Reemplaza las URLs de Unsplash por tus propias imágenes.

## 🌐 URL del sitio

Una vez desplegado, tu invitación estará disponible en:

```
https://TU-USUARIO.github.io/invitacion-15-anos-valentina
```

## 📱 Compartir la invitación

Puedes compartir la URL directamente o crear un código QR que apunte a tu página para incluir en invitaciones físicas.

## 🔧 Tecnologías utilizadas

- HTML5
- CSS3 (con Flexbox y Grid)
- JavaScript ES6+
- GitHub Pages para hosting

---

🎂 **¡Que tengas una celebración increíble!** 💖
