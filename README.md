# Portfolio Web - Desarrollador Web

Un portfolio web moderno y profesional construido con **Astro** y **Tailwind CSS**. Diseñado para desarrolladores web que quieren mostrar sus proyectos, habilidades y experiencia de manera atractiva.

## 🚀 Características

- **Diseño Moderno**: Interfaz limpia y profesional con gradientes y animaciones
- **Totalmente Responsive**: Optimizado para todos los dispositivos
- **SEO Optimizado**: Meta tags y estructura semántica
- **Navegación Suave**: Scroll suave entre secciones
- **Filtros de Proyectos**: Categorización por tipo de proyecto
- **Formulario de Contacto**: Integrado y funcional
- **Animaciones**: Efectos visuales atractivos
- **Rendimiento Optimizado**: Carga rápida con Astro

## 📋 Secciones Incluidas

1. **Hero Section**: Presentación personal con llamadas a la acción
2. **Sobre Mí**: Información personal y profesional
3. **Proyectos**: Portfolio de trabajos con filtros
4. **Habilidades**: Técnicas y blandas con barras de progreso
5. **Experiencia**: Laboral y educativa con línea de tiempo
6. **Contacto**: Formulario e información de contacto
7. **Footer**: Enlaces y información adicional

## 🛠️ Tecnologías Utilizadas

- **Astro**: Framework para sitios estáticos
- **Tailwind CSS**: Framework de CSS utility-first
- **JavaScript**: Interactividad y animaciones
- **HTML5**: Estructura semántica
- **CSS3**: Estilos y animaciones personalizadas

## 📦 Instalación

1. **Clona el repositorio**:
   ```bash
   git clone <tu-repositorio>
   cd portfolio
   ```

2. **Instala las dependencias**:
   ```bash
   npm install
   ```

3. **Ejecuta el servidor de desarrollo**:
   ```bash
   npm run dev
   ```

4. **Abre tu navegador** en `http://localhost:4321`

## 🎨 Personalización

### 1. Información Personal

Edita los siguientes archivos para personalizar tu información:

- **`src/components/Hero.astro`**: Datos del hero (nombre, título, descripción)
- **`src/components/About.astro`**: Información personal y profesional
- **`src/components/Contact.astro`**: Información de contacto

### 2. Proyectos

Modifica el array `projects` en **`src/components/Projects.astro`**:

```javascript
const projects = [
  {
    title: "Nombre del Proyecto",
    description: "Descripción del proyecto",
    image: "/ruta-a-la-imagen.jpg",
    technologies: ["React", "Node.js", "MongoDB"],
    github: "https://github.com/tu-usuario/proyecto",
    demo: "https://demo-del-proyecto.com",
    category: "Full Stack"
  }
  // ... más proyectos
];
```

### 3. Habilidades

Actualiza las habilidades en **`src/components/Skills.astro`**:

```javascript
const skillCategories = [
  {
    name: "Frontend",
    skills: [
      { name: "HTML5", level: 90 },
      { name: "CSS3", level: 85 },
      // ... más habilidades
    ]
  }
];
```

### 4. Experiencia

Modifica la experiencia en **`src/components/Experience.astro`**:

```javascript
const experience = [
  {
    title: "Tu Cargo",
    company: "Nombre de la Empresa",
    period: "2023 - Presente",
    location: "Ciudad, País",
    description: "Descripción de tus responsabilidades",
    technologies: ["React", "Node.js", "MongoDB"]
  }
];
```

### 5. Colores y Estilos

Los colores principales se pueden modificar en **`src/styles/global.css`**:

```css
.btn-primary {
  @apply bg-blue-600 hover:bg-blue-700; /* Cambia los colores aquí */
}

.gradient-text {
  @apply bg-gradient-to-r from-blue-600 to-purple-600; /* Gradiente principal */
}
```

### 6. Imágenes

- Reemplaza las imágenes de placeholder en los componentes
- Agrega tu foto de perfil en la sección Hero
- Incluye capturas de pantalla de tus proyectos

## 📧 Configuración del Formulario de Contacto

El formulario de contacto está configurado para mostrar un mensaje de confirmación. Para hacerlo funcional, puedes:

1. **Usar EmailJS**:
   ```bash
   npm install emailjs-com
   ```

2. **Usar Formspree**:
   - Regístrate en [Formspree](https://formspree.io)
   - Reemplaza la acción del formulario

3. **Usar Netlify Forms**:
   - El formulario funcionará automáticamente en Netlify

## 🚀 Despliegue

### Netlify (Recomendado)

1. Conecta tu repositorio a Netlify
2. Configura el comando de build: `npm run build`
3. Configura el directorio de publicación: `dist`

### Vercel

1. Conecta tu repositorio a Vercel
2. Vercel detectará automáticamente que es un proyecto Astro

### GitHub Pages

1. Ejecuta `npm run build`
2. Sube el contenido de `dist` a la rama `gh-pages`

## 📱 Optimización para Móviles

El portfolio está completamente optimizado para dispositivos móviles con:

- Navegación responsive
- Imágenes adaptativas
- Tipografía escalable
- Touch-friendly interactions

## 🔧 Scripts Disponibles

- `npm run dev`: Servidor de desarrollo
- `npm run build`: Construcción para producción
- `npm run preview`: Vista previa de la construcción
- `npm run astro ...`: Comandos adicionales de Astro

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de usarlo y modificarlo para tu portfolio personal.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o pull request para sugerencias o mejoras.

## 📞 Soporte

Si tienes alguna pregunta o necesitas ayuda, no dudes en contactarme.

---

**¡Disfruta creando tu portfolio profesional!** 🎉
