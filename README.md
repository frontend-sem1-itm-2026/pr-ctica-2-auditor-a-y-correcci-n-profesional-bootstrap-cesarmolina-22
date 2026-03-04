[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/B616wQpB)
# PRÁCTICA 2 — Auditoría y Corrección Profesional (Bootstrap)

## 🎯 Objetivo
Recibirás una plantilla con errores. Debes **auditar**, **corregir** y **profesionalizar** la página usando Bootstrap.

---

## 🧩 Errores intencionales que debes detectar (hay varios)
Ejemplos (no son los únicos):
- Imagen sin `img-fluid`
- `href="#"` sin funcionalidad
- Cards sin `h-100` (alturas disparejas)
- Navbar sin `collapse` correcto (toggler no abre)
- Sin spacing (se ve “pegado”)
- Columnas mal distribuidas (ej. 5 + 8)
- Falta viewport (responsive falla)

---

## ✅ Lo que debes lograr (Checklist)
### 1) Navbar profesional y funcional
- Debe tener: `container`, `navbar-brand`, `navbar-toggler`, `collapse`
- Los links deben navegar a secciones reales: `#sobre-mi`, `#proyectos`, `#contacto`
- Debe funcionar en móvil (hamburguesa)

### 2) Responsive real (Mobile First)
- Asegura que exista `meta viewport`
- Usa estrategia de columnas: `col-12 col-md-* col-lg-*` cuando aplique

### 3) Grid coherente (12 columnas)
- Corrige el bloque que tiene `5 + 8` (debe sumar 12 o usar `col` automático)
- Debe verse correcto en móvil y en escritorio

### 4) Jerarquía visual (diseño profesional)
En las cards de Proyectos aplica:
- Imagen → llama atención
- Título → informa
- Texto → explica
- Botón → acción

### 5) Cards consistentes
- Todas deben tener misma altura: `h-100`
- Sombra ligera: `shadow-sm`
- Espaciado entre columnas: `g-4`

### 6) Navegación real (UX)
- Nada de `href="#"`
- Opcional recomendado: `scroll-behavior: smooth;`

---

## 🧪 Evaluación (rubrica)
Se evalúa:
- **Criterio** (detectas y justificas cambios)
- **Coherencia** (grid correcto, secciones ordenadas)
- **Uso correcto de clases** (Bootstrap, no “parches”)
- **Limpieza** (HTML claro, indentación, sin basura)

---

## 📌 Entrega (obligatorio)
1. Realiza cambios hasta que la página se vea profesional.
2. Haz commit final con este mensaje EXACTO:

**Practica 2: auditoria y correccion profesional**

> Nota: si haces varios commits durante el proceso, está bien, pero el último debe tener ese mensaje.

---

## 🧠 Consejo
Bootstrap es sistema, no decoración. Si lo arreglas con CSS en lugar de clases, pierdes puntos.
