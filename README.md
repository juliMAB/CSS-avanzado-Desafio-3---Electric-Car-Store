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

## 📱 Breakpoints Implementados

- **Mobile**: < 576px con menú hamburguesa
- **Tablet**: 576px - 992px con layout híbrido
- **Desktop**: 993px+ con layout vertical completo

## 🚀 Estado del Desarrollo - COMPLETADO ✅

### Commit Final: Proyecto 100% Funcional

**Fecha**: 9 de Enero, 2025

**Estado**: ✅ **DESAFÍO COMPLETADO**

**Logros conseguidos:**
- ✅ **Estructura HTML completa** con las 4 secciones requeridas
- ✅ **Variables CSS implementadas** para consistencia de colores
- ✅ **3 Layouts responsive** (Mobile, Tablet, Desktop) con CSS Grid
- ✅ **Menú hamburguesa funcional** para móviles
- ✅ **Grid de productos completo** con 8 tarjetas
- ✅ **Sistema de paginación** con navegación
- ✅ **Flexbox implementado** en todas las secciones
- ✅ **JavaScript funcional** para interactividad
- ✅ **Hover effects** y transiciones suaves
- ✅ **Scrollbar personalizado** en grid de productos

**Variables de colores definidas:**
```css
:root {
    --primary-color: #00579c;    /* Azul principal */
    --background-color: #ffffff; /* Blanco */
    --secondary-color: #012f6b;  /* Azul oscuro */
    --tertiary-color: #e2e2e2;   /* Gris aside */
    --border-color: #8f8f8f;    /* Color de bordes */
}
```

**Funcionalidades implementadas:**

**Navegación responsiva:**
- 🚗 Electric Cars (título con ícono)
- Menú completo: Inicio, Catalogo, Ofertas, Contacto
- **Menú hamburguesa animado** para móviles
- **Layout adaptativo** según breakpoint

**Sección Principal:**
- **Grid de productos** con 8 tarjetas de autos eléctricos
- **Scrollbar personalizado** con colores corporativos
- **Sistema de paginación** con navegación anterior/siguiente
- **Hover effects** en tarjetas (elevación y sombra)
- **Botones "Ver más"** con transiciones

**Aside funcional:**
- Selector "Ordenar Por" con opciones:
  - Precio, Nombre, Marca, Autonomía
- **Responsive** en todos los breakpoints

**Footer completo:**
- Iconos de redes sociales (Facebook, Instagram)
- Copyright con "Todos los derechos reservados"
- **Hover effects** en iconos sociales

**Layouts implementados:**

**Desktop (993px+):**
```
┌─────────────────────────────┐
│    nav    │     aside       │  ← Navegación vertical | Filtros
├───────────┼─────────────────┤
│    nav    │     main        │  ← Navegación | Grid productos
├───────────┼─────────────────┤
│  footer   │     main        │  ← Footer | Paginación
└─────────────────────────────┘
```

**Tablet (576px-992px):**
```
┌─────────────────────────────┐
│         nav nav             │  ← Navegación horizontal + hamburguesa
├─────────────┬───────────────┤
│    aside    │     main      │  ← Filtros | Grid productos (2 cols)
├─────────────┴───────────────┤
│    footer footer            │  ← Footer completo
└─────────────────────────────┘
```

**Mobile (< 576px):**
```
┌─────────────────────────────┐
│            nav              │  ← Navegación + hamburguesa
├─────────────────────────────┤
│           aside             │  ← Filtros
├─────────────────────────────┤
│           main              │  ← Grid productos (1 col)
├─────────────────────────────┤
│          footer             │  ← Footer
└─────────────────────────────┘
```

**JavaScript implementado:**
```javascript
// Funcionalidad del menú hamburguesa
const hamburgerBtn = document.getElementById('hamburgerBtn');
const navMenu = document.getElementById('navMenu');

hamburgerBtn.addEventListener('click', () => {
    hamburgerBtn.classList.toggle('active');
    navMenu.classList.toggle('active');
});
```

**Características técnicas destacadas:**

**CSS Grid avanzado:**
- ✅ `grid-template-areas` en 3 layouts diferentes
- ✅ Columnas adaptativas según breakpoint
- ✅ Filas optimizadas para cada dispositivo

**Flexbox completo:**
- ✅ Navegación con distribución horizontal/vertical
- ✅ Footer con redes sociales centradas
- ✅ Tarjetas de productos con contenido centrado
- ✅ Aside con filtros organizados

**Funcionalidades avanzadas:**
- ✅ **Menú hamburguesa animado** (transformación en X)
- ✅ **Scrollbar personalizado** en grid de productos
- ✅ **Hover effects** en tarjetas (elevación y sombra)
- ✅ **Transiciones suaves** en todos los elementos
- ✅ **Sistema de paginación** con botones funcionales

## 📁 Estructura del Proyecto

```
├── index.html                 ← HTML completo con JavaScript
├── assets/
│   ├── css/
│   │   └── style.css         ← CSS optimizado y sin repeticiones
│   └── img/
│       └── car.webp          ← Imagen de productos
├── ref/
│   ├── doc/
│   │   └── Desafio_txt_Plano.txt
│   └── img/
│       ├── img6.jpg
│       ├── img14.jpg
│       └── img20.jpg
├── Progress/
│   └── commit-final.png      ← Captura proyecto terminado
└── README.md                 ← Este archivo
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica completa
- **CSS3**: Estilos avanzados y animaciones
- **CSS Grid**: 3 layouts con `grid-template-areas`
- **Flexbox**: Distribución en todas las secciones
- **CSS Variables**: Gestión de colores corporativos
- **Media Queries**: 3 breakpoints responsive
- **JavaScript**: Funcionalidad del menú hamburguesa
- **Font Awesome**: Iconos (auto, redes sociales, navegación)

## 🎯 Estado Final de Requerimientos

| Requerimiento | Estado | Puntos | Implementación |
|---------------|--------|---------|----------------|
| 2 layouts diferentes (Mobile/Desktop) | ✅ | 3/3 | 3 layouts: Mobile, Tablet, Desktop |
| CSS Grid con grid-template-areas | ✅ | 3/3 | Implementado en todos los breakpoints |
| Flexbox para distribución | ✅ | 2/2 | Todas las secciones utilizan Flexbox |
| 4 secciones principales | ✅ | 2/2 | Nav, Aside, Main, Footer completos |
| **Total conseguido** | ✅ | **10/10** | **100% COMPLETADO** |

### 📊 Funcionalidades extra implementadas:

**Más allá de los requerimientos:**
- ✅ **Menú hamburguesa animado** con transformación suave
- ✅ **Grid de productos completo** con 8 tarjetas
- ✅ **Sistema de paginación** con navegación
- ✅ **Scrollbar personalizado** con colores corporativos
- ✅ **Hover effects avanzados** en todos los elementos
- ✅ **3 breakpoints responsive** (requerían solo 2)
- ✅ **JavaScript funcional** para interactividad
- ✅ **Optimización de código** sin repeticiones

## 🏆 Logros Técnicos Destacados

### 🎨 Diseño responsivo completo:
- **Mobile First**: Layout base optimizado para móviles
- **Progressive Enhancement**: Mejoras progresivas para tablets y desktop
- **Menú hamburguesa**: Funcionalidad completa con animaciones

### 🔧 Código optimizado:
- **CSS limpio**: Sin repeticiones, variables organizadas
- **Flexbox estratégico**: Implementado donde aporta valor
- **Grid inteligente**: Columnas adaptativas según dispositivo

### ⚡ Interactividad avanzada:
- **JavaScript modular**: Funcionalidad del menú hamburguesa
- **Transiciones suaves**: Hover effects en tarjetas y botones
- **UX optimizada**: Navegación intuitiva en todos los dispositivos

## 🎓 Aprendizajes Clave

1. **CSS Grid con grid-template-areas** para layouts complejos
2. **Combinación Grid + Flexbox** para máximo control
3. **Mobile First** como estrategia de desarrollo
4. **Media Queries estratégicas** para breakpoints específicos
5. **Optimización de código** eliminando repeticiones
6. **JavaScript vanilla** para funcionalidades básicas

---

**Desarrollado por**: Julian Aguirre  
**Curso**: CSS Avanzado - Desafío Latam  
**Fecha**: Enero 2025  
**Desafío**: 3 - Electric Car Store  
**Estado**: ✅ **COMPLETADO AL 100%**

**Puntuación obtenida**: 10/10 puntos + funcionalidades extra
