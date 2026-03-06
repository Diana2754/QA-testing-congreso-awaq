# Regression Checklist – Web Informativa

## Información General

- **Versión:** 1.1  
- **Cambio aplicado:** Rediseño del header (estructura y estilos CSS)  
- **Tester:** Tu Nombre  
- **Fecha:** XX/XX/XXXX  
- **Ambiente:** Staging  
- **Navegadores:** Chrome, Firefox  
- **Dispositivos:** Desktop (1920px), Tablet (768px), Mobile (375px)

---

## 1. Navegación y Enlaces

### Header
- [ ] El logo redirige correctamente al Home
- [ ] El menú principal redirige a las secciones correctas
- [ ] Los submenús se despliegan correctamente (si aplica)
- [ ] No existen enlaces rotos (error 404)
- [ ] Los links externos abren en nueva pestaña (si corresponde)
- [ ] El estado hover funciona correctamente
- [ ] El estado activo del menú se visualiza correctamente
- [ ] No hay superposición de elementos al desplegar menú

### Footer
- [ ] Links institucionales funcionan correctamente
- [ ] Enlaces a redes sociales redirigen correctamente
- [ ] Política de privacidad y términos accesibles

---

## 2. Integridad Visual (UI)

- [ ] El header no se superpone con el contenido
- [ ] No hay elementos cortados
- [ ] No hay imágenes pixeladas o deformadas
- [ ] El espaciado entre elementos es consistente
- [ ] No hay textos desalineados
- [ ] No existe scroll horizontal innecesario

---

## 3. Responsive / Adaptabilidad

### Desktop (≥1366px)
- [ ] Layout correcto
- [ ] Sin desbordes visuales

### Tablet (~768px)
- [ ] Menú colapsa correctamente
- [ ] Botón hamburguesa funcional
- [ ] Elementos no se superponen

### Mobile (~375px)
- [ ] Header visible correctamente
- [ ] Botón hamburguesa funcional
- [ ] Links clickeables sin superposición
- [ ] Textos legibles sin zoom
- [ ] No hay scroll horizontal

---

## 4. Formularios (si aplica)

### Validaciones
- [ ] Campo nombre obligatorio validado
- [ ] Campo email obligatorio validado
- [ ] Validación de formato de email correcta
- [ ] Campo mensaje obligatorio validado

### Funcionalidad
- [ ] Botón enviar responde correctamente
- [ ] No permite envío con campos vacíos
- [ ] Mensaje de éxito visible tras envío
- [ ] No permite doble envío rápido

---

## 5. Compatibilidad Cross-Browser

- [ ] Visualización correcta en Chrome
- [ ] Visualización correcta en Firefox
- [ ] No existen diferencias críticas entre navegadores

---

## 6. Performance Básica

- [ ] Página carga correctamente
- [ ] No hay errores en consola (DevTools)
- [ ] Elementos del header cargan sin demora visible

---

## 7. Accesibilidad Básica

- [ ] Navegación posible con tecla TAB
- [ ] Foco visible al navegar con teclado
- [ ] Imágenes poseen atributo alt
- [ ] Contraste de colores adecuado
- [ ] Botones tienen etiqueta descriptiva

---

## Observaciones

_(Espacio para registrar hallazgos durante la ejecución de la regresión)_