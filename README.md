# Electric Car Store - Desafío 3 CSS Avanzado

## 📋 Descripción del Proyecto

Este proyecto es parte del **Desafío 3** de CSS avanzado de **Desafío Latam**, enfocado en validar conocimientos de media queries y breakpoints aplicados al diseño de layouts responsivos para mostrar productos de autos eléctricos.

## 🎯 Requerimientos del Desafío

1. **Diseñar 2 layouts diferentes** (Mobile y Desktop)
   - La versión de escritorio debe activarse sobre los 576px **(3 puntos)**

2. **Utilizar CSS Grid** con la propiedad `grid-template-areas` para diseñar los diferentes layouts **(3 puntos)**

3. **Utilizar Flexbox** para distribuir los elementos dentro de cada sección de los layouts **(2 puntos)**

4. **4 secciones principales requeridas** **(2 puntos)**:
   - Menú de navegación
   - Sección de filtros de búsqueda (aside)
   - Sección Principal
   - Pie de página

## 📱 Breakpoints Definidos

- **Desktop**: 576px en adelante (única versión desarrollada actualmente)
- **Opcional Tablet**: ≥ 576px (no evaluado)
- **Opcional Large Desktop**: ≥ 992px (no evaluado)

## 🚀 Progreso del Desarrollo

### Commit 1: Layout Base Desktop con CSS Grid ✅

**Fecha**: 9 de Julio, 2025

**Estado actual**: Desktop funcional con contenido básico

**Logros conseguidos:**
- ✅ Estructura HTML básica con las 4 secciones requeridas
- ✅ Variables CSS implementadas para consistencia de colores
- ✅ Layout Desktop con CSS Grid y `grid-template-areas`
- ✅ Separación correcta de CSS en archivo externo
- ✅ Media query funcional para Desktop (576px+)
- ✅ **Navegación completa** con título, ícono y menú
- ✅ **Footer con redes sociales** (Facebook, Instagram) y copyright
- ✅ **Aside con filtros** (selector "Ordenar Por")
- ✅ **Flexbox implementado** en navegación y footer

**Variables de colores definidas:**
```css
:root {
    --primary-color: #00579c;    /* Azul principal */
    --background-color: #ffffff; /* Blanco */
    --secondary-color: #012f6b;  /* Azul oscuro */
    --tertiary-color: #e2e2e2;   /* Gris aside */
}
```

**Contenido implementado:**

**Navegación:**
- 🚗 Electric Cars (título con ícono)
- Menú: Inicio, Catalogo, Ofertas, Contacto
- Layout vertical centrado con Flexbox

**Aside:**
- Selector "Ordenar Por" con opciones:
  - Precio (por defecto)
  - Nombre, Marca, Autonomía

**Footer:**
- Iconos de redes sociales con hover effects
- Texto "Todos los derechos reservados"
- Layout con Flexbox

**Layout Desktop (576px+):**
```
┌─────────────────────────────┐
│         nav nav             │  ← 🚗 Electric Cars + Menú
├─────────────┬───────────────┤
│    aside    │     main      │  ← Filtros | Contenido principal
│ Ordenar Por │               │
├─────────────┴───────────────┤
│    footer footer            │  ← 📱📘 + Copyright
└─────────────────────────────┘
```

**Grid template areas implementadas:**
```css
grid-template-areas: 
    "nav nav"
    "aside main"
    "footer footer";
grid-template-columns: 200px 1fr; /* Aside optimizado */
```

**Captura de pantalla:**

![Composición desktop con contenido](Progress/Commit_2.PNG)

*Layout desktop completo con navegación, filtros y footer funcionales*

## 📁 Estructura del Proyecto

```
├── index.html
├── assets/
│   └── css/
│       └── style.css
├── ref/
│   ├── doc/
│   │   └── Desafio_txt_Plano.txt
│   └── img/
│       ├── img6.jpg
│       ├── img14.jpg
│       └── img20.jpg
├── Progress/
│   └── commit-1-desktop-layout.png
└── README.md
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos y layout
- **CSS Grid**: Layout principal con `grid-template-areas`
- **Flexbox**: Distribución de elementos en navegación y footer
- **CSS Variables**: Gestión consistente de colores
- **Media Queries**: Diseño responsive
- **Font Awesome**: Iconos (auto, redes sociales)

## 📋 Próximos Pasos

### Pendientes para completar el desafío:

- [ ] **Desarrollar layout Mobile** (< 576px)
- [ ] **Crear grid de productos** en la sección main
- [ ] **Agregar más filtros** en el aside (marca, precio, autonomía)
- [ ] **Implementar menú hamburguesa** para mobile
- [ ] **Optimizar responsive** para diferentes pantallas

### Funcionalidades ya implementadas:
- ✅ **Navegación con Flexbox** (título + menú vertical)
- ✅ **Footer con Flexbox** (redes sociales + copyright)
- ✅ **Aside funcional** con selector de ordenamiento
- ✅ **Variables CSS** para consistencia de colores
- ✅ **Hover effects** en elementos interactivos

## 🎨 Estado de Requerimientos Técnicos

| Requerimiento | Estado | Puntos | Progreso |
|---------------|--------|---------|----------|
| 2 layouts diferentes (Mobile/Desktop) | 🔄 | 1.5/3 | Solo Desktop completo |
| CSS Grid con grid-template-areas | ✅ | 3/3 | Completo y optimizado |
| Flexbox para distribución | ✅ | 2/2 | Implementado en nav y footer |
| 4 secciones principales | ✅ | 2/2 | Todas con contenido funcional |
| **Total actual** | **8.5/10** | **85%** | **Muy cerca del objetivo** |

### 📊 Detalles de implementación:

**Flexbox implementado en:**
- ✅ Navegación: Disposición vertical centrada de menú
- ✅ Footer: Distribución de redes sociales y copyright
- ✅ Aside: Organización de filtros
- ✅ Elementos con hover effects y transiciones

**CSS Grid optimizado:**
- ✅ Layout responsive con `grid-template-areas`
- ✅ Columnas ajustadas: `200px 1fr` para mejor proporción
- ✅ Áreas claramente definidas y funcionales

## 🎯 Enfoque de Desarrollo

Siguiendo las recomendaciones del desafío:
1. ✅ **Layout base construido** con CSS Grid
2. ✅ **Flexbox implementado** en secciones internas
3. ✅ **Contenido funcional** agregado a todas las secciones
4. 🔄 **Versión móvil pendiente** (próximo paso)
5. ✅ **Font Awesome integrado** para iconografía

### 🎨 Características destacadas:
- **Responsive design** con media queries
- **Variables CSS** para mantenimiento fácil
- **Hover effects** y transiciones suaves
- **Tipografía consistente** y legible
- **Colores corporativos** aplicados sistemáticamente

---

**Desarrollado por**: Julian Aguirre  
**Curso**: CSS Avanzado - Desafío Latam  
**Fecha**: Julio 2025  
**Desafío**: 3 - Electric Car Store
