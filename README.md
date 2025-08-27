# Portfolio - Desarrollador Backend

Un portfolio profesional y moderno para desarrolladores backend, diseñado para mostrar proyectos, habilidades y experiencia técnica.

## 🚀 Características

- **Diseño Responsive**: Se adapta perfectamente a todos los dispositivos
- **Navegación Suave**: Scroll automático a las secciones
- **Animaciones**: Efectos visuales atractivos y profesionales
- **Formulario de Contacto**: Con validación y notificaciones
- **Optimizado para SEO**: Estructura HTML semántica
- **Fácil Personalización**: Variables CSS para cambiar colores y estilos

## 📁 Estructura del Proyecto

```
Portfolio/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidad JavaScript
└── README.md           # Este archivo
```

## 🎨 Personalización

### 1. Información Personal

Edita el archivo `index.html` y cambia:

- **Nombre**: Reemplaza "Tu Nombre" en múltiples lugares
- **Descripción**: Modifica la descripción en la sección hero
- **Experiencia**: Actualiza los números en la sección "Sobre Mí"
- **Proyectos**: Personaliza los proyectos con tu información real
- **Contacto**: Cambia email, LinkedIn y GitHub

### 2. Colores y Estilos

Modifica las variables CSS en `styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Color principal */
    --secondary-color: #1e40af;    /* Color secundario */
    --accent-color: #3b82f6;       /* Color de acento */
    --text-primary: #1f2937;       /* Texto principal */
    --text-secondary: #6b7280;     /* Texto secundario */
    --bg-primary: #ffffff;         /* Fondo principal */
    --bg-secondary: #f8fafc;       /* Fondo secundario */
}
```

### 3. Proyectos

Para añadir o modificar proyectos, edita la sección en `index.html`:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-icon-name"></i>  <!-- Cambia el ícono -->
    </div>
    <div class="project-content">
        <h3>Nombre del Proyecto</h3>
        <p>Descripción del proyecto...</p>
        <div class="project-tech">
            <span>Tecnología 1</span>
            <span>Tecnología 2</span>
        </div>
        <div class="project-links">
            <a href="URL_DEL_DEMO" class="btn btn-small">Ver Demo</a>
            <a href="URL_DEL_CODIGO" class="btn btn-small btn-outline">Código</a>
        </div>
    </div>
</div>
```

### 4. Herramientas y Tecnologías

Personaliza las tecnologías en la sección correspondiente:

```html
<div class="tool-item">
    <i class="fab fa-tecnologia"></i>  <!-- Ícono de FontAwesome -->
    <span>Nombre de la Tecnología</span>
</div>
```

## 🌐 Despliegue en Netlify

### Opción 1: Drag & Drop (Más Fácil)

1. Ve a [netlify.com](https://netlify.com)
2. Crea una cuenta o inicia sesión
3. Arrastra la carpeta del proyecto a la zona de deploy
4. ¡Listo! Tu portfolio estará online

### Opción 2: Desde GitHub

1. Sube tu código a GitHub
2. Conecta tu repositorio a Netlify
3. Configura el build (no es necesario para sitios estáticos)
4. Deploy automático en cada push

### Opción 3: Netlify CLI

```bash
# Instalar Netlify CLI
npm install -g netlify-cli

# Iniciar sesión
netlify login

# Deploy
netlify deploy

# Deploy a producción
netlify deploy --prod
```

## 🔧 Funcionalidades JavaScript

- **Navegación Móvil**: Menú hamburguesa responsive
- **Scroll Suave**: Navegación interna con animaciones
- **Formulario de Contacto**: Validación y notificaciones
- **Animaciones**: Efectos al hacer scroll
- **Contadores Animados**: Estadísticas con animación
- **Header Inteligente**: Se oculta/muestra según el scroll

## 📱 Responsive Design

El portfolio está optimizado para:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🎯 SEO y Performance

- **Meta tags** optimizados
- **Estructura HTML** semántica
- **Imágenes lazy loading** (preparado para futuras implementaciones)
- **CSS optimizado** con variables y reutilización
- **JavaScript modular** y eficiente

## 🚀 Próximas Mejoras

- [ ] Modo oscuro
- [ ] Filtros de proyectos por tecnología
- [ ] Blog integrado
- [ ] Sistema de comentarios
- [ ] Analytics integrado
- [ ] PWA (Progressive Web App)

## 📞 Soporte

Para personalizar o mejorar tu portfolio:

1. **Revisa el código**: Los archivos están bien comentados
2. **Modifica gradualmente**: Haz cambios pequeños y prueba
3. **Usa las herramientas del navegador**: Inspecciona elementos para entender la estructura

## 📄 Licencia

Este proyecto es de código abierto y puedes usarlo libremente para tu portfolio personal.

---

**¡Tu portfolio está listo para impresionar! 🎉**

Recuerda personalizar toda la información con tus datos reales antes de hacer el deploy.
