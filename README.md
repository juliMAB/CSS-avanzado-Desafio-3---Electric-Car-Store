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

**Estado actual**: Solo desarrollado para **Desktop** (576px+)

**Logros conseguidos:**
- ✅ Estructura HTML básica con las 4 secciones requeridas
- ✅ Variables CSS implementadas para consistencia de colores
- ✅ Layout Desktop con CSS Grid y `grid-template-areas`
- ✅ Separación correcta de CSS en archivo externo
- ✅ Media query funcional para Desktop (576px+)

**Variables de colores definidas:**
```css
:root {
    --primary-color: #00579c;    /* Azul principal */
    --background-color: #ffffff; /* Blanco */
    --secondary-color: #012f6b;  /* Azul oscuro */
    --tertiary-color: #e2e2e2;   /* Gris aside */
}
```

**Layout Desktop (576px+):**
```
┌─────────────────────────────┐
│         nav nav             │  ← Navegación completa
├─────────────┬───────────────┤
│    aside    │     main      │  ← Filtros | Contenido principal
├─────────────┴───────────────┤
│       footer footer         │  ← Pie de página completo
└─────────────────────────────┘
```

**Grid template areas implementadas:**
```css
grid-template-areas: 
    "nav nav"
    "aside main"
    "footer footer";
grid-template-columns: 250px 1fr;
```

**Captura de pantalla:**

![Primera composición desktop](Progress/commit-1-desktop-layout.png)

*Primera impresión lograda jugando con @media queries para conseguir la composición requerida para PC*

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
- **CSS Variables**: Gestión consistente de colores
- **Media Queries**: Diseño responsive

## 📋 Próximos Pasos

### Pendientes para completar el desafío:

- [ ] **Desarrollar layout Mobile** (< 576px)
- [ ] **Implementar Flexbox** para distribución interna de elementos
- [ ] **Agregar contenido a la navegación** (menú con ícono hamburguesa para mobile)
- [ ] **Implementar filtros** en el aside
- [ ] **Crear grid de productos** en la sección main
- [ ] **Agregar contenido al footer**

### Consideraciones técnicas:
- El ícono hamburguesa solo debe visualizarse (sin interacción)
- Usar Material Design Icons o similares
- Cambiar orientación del menú según breakpoint
- Ocultar subsección derecha en mobile y mostrar solo ícono

## 🎨 Estado de Requerimientos Técnicos

| Requerimiento | Estado | Puntos | Progreso |
|---------------|--------|---------|----------|
| 2 layouts diferentes (Mobile/Desktop) | 🔄 | 1.5/3 | Solo Desktop |
| CSS Grid con grid-template-areas | ✅ | 3/3 | Completo |
| Flexbox para distribución | ❌ | 0/2 | Pendiente |
| 4 secciones principales | ✅ | 2/2 | Completo |
| **Total actual** | **6.5/10** | **65%** |

## 🎯 Enfoque de Desarrollo

Siguiendo las recomendaciones del desafío:
1. ✅ **Iniciado con construcción del layout base**
2. 🔄 **Pendiente: Desarrollar versión móvil**
3. ❌ **Pendiente: Implementar Flexbox**
4. ❌ **Pendiente: Agregar contenido y funcionalidad**

---

**Desarrollado por**: Julian Aguirre  
**Curso**: CSS Avanzado - Desafío Latam  
**Fecha**: Julio 2025  
**Desafío**: 3 - Electric Car Store
