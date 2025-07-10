# Electric Car Store - Desafío 3 CSS Avanzado

## 📋 Descripción del Proyecto

Este proyecto es parte del **Desafío 3** de CSS avanzado de **Desafío Latam**, enfocado en validar conocimientos de media queries y breakpoints aplicados al diseño de layouts responsivos para mostrar productos de autos eléctricos.

## 🎯 Estado Final de Requerimientos

| Requerimiento | Estado | Puntos | Implementación |
|---------------|--------|---------|----------------|
| 2 layouts diferentes (Mobile/Desktop) | ✅ | 3/3 | 3 layouts: Mobile, Tablet, Desktop |
| CSS Grid con grid-template-areas | ✅ | 3/3 | Implementado en todos los breakpoints |
| Flexbox para distribución | ✅ | 2/2 | Todas las secciones utilizan Flexbox |
| 4 secciones principales | ✅ | 2/2 | Nav, Aside, Main, Footer completos |
| **Total conseguido** | ✅ | **10/10** | **100% COMPLETADO** |

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

---

**Desarrollado por**: Julian Aguirre  
**Curso**: CSS Avanzado - Desafío Latam  
**Desafío**: 3 - Electric Car Store  
