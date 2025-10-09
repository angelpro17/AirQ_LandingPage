# AirQ Landing Page - Oxaira

Una landing page moderna y responsive para AirQ, el sistema de monitoreo de calidad del aire IoT desarrollado por Oxaira.

## 🌟 Características

- **Diseño Responsive**: Optimizado para dispositivos móviles, tablets y desktop
- **Accesibilidad**: Cumple con estándares WCAG 2.1 AA
- **Performance**: Optimizado para carga rápida y SEO
- **Interactividad**: FAQ con acordeón, validación de formularios, y navegación suave
- **Moderno**: Usa tecnologías web actuales y mejores prácticas

## 📁 Estructura del Proyecto

```
/
├── index.html          # Archivo HTML principal
├── styles.css          # Hoja de estilos CSS
├── assets/             # Carpeta de recursos
│   ├── LogoOxaira.png     # Logo de la empresa
│   ├── product.png        # Imagen del producto/app
│   ├── renato-profile.JPG # Foto del equipo
│   ├── Diego_Ramirez.jpeg # Foto del equipo
│   ├── Luis_Angel.jpeg    # Foto del equipo
│   └── andres.jpg         # Foto del equipo
└── README.md           # Documentación del proyecto
```

## 🚀 Características Técnicas

### HTML5 Semántico
- Uso de elementos semánticos (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- Estructura clara y accesible
- Metadatos optimizados para SEO y redes sociales

### CSS Moderno
- Mobile-first responsive design
- CSS Grid y Flexbox para layouts
- Variables CSS para mantenimiento fácil
- Animaciones y transiciones suaves
- Soporte para modo oscuro y alto contraste

### Accesibilidad
- Navegación por teclado completa
- Atributos ARIA apropiados
- Contraste de colores WCAG AA
- Soporte para lectores de pantalla
- Skip links para navegación rápida

### Performance
- Imágenes optimizadas
- CSS y recursos precargados
- Código limpio y optimizado
- Lazy loading preparado

## 📱 Breakpoints Responsive

- **Mobile Small**: ≤ 480px
- **Mobile**: ≤ 768px  
- **Tablet**: ≤ 1024px
- **Desktop**: > 1024px
- **Large Desktop**: ≥ 1400px

## 🎨 Paleta de Colores

- **Azul Primario**: #207193 (Headers, CTA)
- **Naranja Acento**: #F18F01 (Botones, elementos destacados)
- **Azul Secundario**: #2E86AB (Botones secundarios)
- **Verde Estado**: #4CAF50 (Indicadores positivos)
- **Amarillo Advertencia**: #FBC02D (Indicadores moderados)
- **Rojo Alerta**: #F44336 (Indicadores negativos)
- **Gris Texto**: #333333 (Texto principal)
- **Gris Claro**: #F7F9FC (Fondos de sección)

## 🔧 Funcionalidades JavaScript

### FAQ Interactivo
- Acordeón con animaciones
- Estados aria-expanded
- Iconos que rotan al expandir

### Formulario de Contacto
- Validación en tiempo real
- Mensajes de error accesibles
- Prevención de envío inválido

### Navegación
- Smooth scrolling entre secciones
- Menú móvil responsive
- Botón "volver arriba"

### Menu Móvil
- Hamburger menu animado
- Navegación touch-friendly
- Cierre automático al seleccionar

## 🌐 Compatibilidad

- **Navegadores**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **Dispositivos**: iPhone 6+, Android 5+, iPad, tablets y desktop
- **Resoluciones**: 320px - 4K (3840px)

## ⚡ Optimizaciones

### SEO
- Meta tags optimizados
- Schema.org structured data
- Open Graph y Twitter Cards
- Título y descripción únicos

### Performance
- Critical CSS inline (preparado)
- Preload de recursos importantes
- Compresión de imágenes
- Minificación preparada

### Accesibilidad
- Contraste AA/AAA
- Navegación por teclado
- Screen reader friendly
- Focus management

## 🚀 Instalación y Uso

1. **Clonar o descargar** los archivos del proyecto
2. **Abrir** `index.html` en un navegador web
3. **Para desarrollo local**: usar un servidor HTTP local

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (http-server)
npx http-server

# Con PHP
php -S localhost:8000
```

## 🔄 Mantenimiento

### Actualizar Imágenes
- Colocar nuevas imágenes en `/assets/`
- Actualizar rutas en `index.html`
- Mantener alt text descriptivo

### Modificar Contenido
- Texto: editar directamente en `index.html`
- Estilos: modificar `styles.css`
- Colores: usar variables CSS en `:root`

### Añadir Secciones
1. Crear nueva sección en HTML
2. Añadir estilos en CSS
3. Actualizar navegación
4. Probar responsive

## 🐛 Solución de Problemas

### Imágenes no cargan
- Verificar rutas en `/assets/`
- Comprobar nombres de archivo
- Revisar permisos de carpeta

### Problemas de responsive
- Verificar meta viewport
- Comprobar media queries
- Usar herramientas de desarrollo

### Problemas de performance
- Optimizar imágenes (WebP, compresión)
- Minificar CSS/JS
- Usar CDN si es necesario

## 📈 Mejoras Futuras

- [ ] Implementar lazy loading de imágenes
- [ ] Añadir animaciones de scroll (AOS)
- [ ] Integrar Google Analytics
- [ ] Añadir formulario funcional con backend
- [ ] Implementar PWA features
- [ ] Añadir modo oscuro manual
- [ ] Optimizar para Core Web Vitals

## 🤝 Contribución

Para contribuir al proyecto:

1. Documentar cambios
2. Probar en múltiples dispositivos
3. Validar accesibilidad
4. Optimizar performance
5. Mantener código limpio

## 📄 Licencia

© 2025 Oxaira. Todos los derechos reservados.

---

**Desarrollado con ❤️ para Oxaira**# AirQ_LandingPage
