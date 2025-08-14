# Know How Soluciones Agrícolas

Un sitio web moderno y responsivo para Know How Soluciones Agrícolas, especialistas en certificaciones orgánicas de aguacate en México.

## 🌱 Características

- **Mobile-first**: Diseñado desde móvil hacia escritorio
- **Responsivo**: Optimizado para todos los tamaños de pantalla
- **Moderno**: Construido con Astro + TailwindCSS v4
- **Accesible**: Implementa buenas prácticas de accesibilidad
- **Rápido**: Optimizado para rendimiento

## 🚀 Tecnologías

- [Astro](https://astro.build/) - Framework web moderno
- [TailwindCSS v4](https://tailwindcss.com/) - Framework CSS utility-first
- TypeScript - Para tipado estático

## 📋 Secciones

1. **Header** - Navegación sticky con logo y contacto
2. **Hero** - Mensaje principal con llamada a la acción
3. **Servicios** - Los 4 servicios principales
4. **Certificaciones** - Organismos certificadores
5. **Contacto** - Información de contacto
6. **Footer** - Información de la empresa

## 🎨 Paleta de Colores

- **Verde principal**: `#16a34a` (green-600)
- **Verde hover**: `#15803d` (green-700)
- **Verde claro**: `#22c55e` (green-500)
- **Grises**: Escala de grises de TailwindCSS

## 📱 Características Móviles

- Email se convierte en ícono en pantallas pequeñas
- Click en el ícono copia el email automáticamente
- Navegación suave entre secciones
- Botón flotante para volver arriba

## 🛠️ Desarrollo

```bash
# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm astro dev

# Construir para producción
pnpm astro build
```

## 📁 Estructura del Proyecto

```
src/
├── components/          # Componentes reutilizables
│   ├── Header.astro    # Navegación principal
│   ├── Hero.astro      # Sección hero
│   ├── Services.astro  # Servicios
│   ├── Certifications.astro # Certificadores
│   ├── Contact.astro   # Contacto
│   └── Footer.astro    # Pie de página
├── layouts/
│   └── main.astro      # Layout principal
├── pages/
│   └── index.astro     # Página principal
└── styles/
    └── global.css      # Estilos globales
```

## 📧 Contacto

- **Email**: brajuba@hotmail.com
- **Ubicación**: Uruapan, Michoacán
