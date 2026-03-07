# Test Plan – Congreso Internacional de Organizaciones Ambientales

## 1. Introducción

Este documento describe el plan de pruebas para el sitio web del **Congreso Internacional de Organizaciones Ambientales**. El objetivo del testing es verificar el correcto funcionamiento del sitio, su integridad visual y su correcta visualización en distintos dispositivos y navegadores.

El sitio es una **web informativa**, que presenta información del evento, cronograma de actividades, organizaciones participantes y un botón de donación mediante PayPal.

---

# 2. Objetivos del Testing

Los objetivos principales de las pruebas son:

- Verificar el correcto funcionamiento de la navegación del sitio.
- Validar la visualización correcta del contenido.
- Detectar problemas de interfaz de usuario (UI).
- Evaluar la experiencia de usuario (UX).
- Comprobar la correcta adaptación del sitio a distintos dispositivos (responsive).
- Verificar la funcionalidad del botón de donaciones.
- Identificar defectos antes de la liberación del sitio.

---

# 3. Alcance del Testing

Las pruebas cubrirán los siguientes componentes del sitio:

### Componentes incluidos

- Header y menú de navegación
- Logo del congreso
- Carrusel de imágenes
- Sección "Nosotros"
- Información del evento
- Cronograma de actividades
- Botón de donación (PayPal)
- Footer
- Enlaces externos
- Adaptabilidad responsive
- Integridad visual del sitio

### Componentes excluidos

El siguiente aspecto no será evaluado en este plan:

- Procesamiento interno del pago en PayPal (plataforma externa)

---

# 4. Tipos de Testing

Se realizarán los siguientes tipos de pruebas:

- **Testing funcional**
- **Testing de interfaz de usuario (UI)**
- **Testing de experiencia de usuario (UX)**
- **Testing responsive**
- **Testing cross-browser**
- **Testing de regresión**

---

# 5. Estrategia de Testing

Las pruebas se ejecutarán manualmente utilizando **casos de prueba y checklist de regresión**.

El proceso de testing seguirá las siguientes etapas:

1. Revisión del sitio web.
2. Ejecución de casos de prueba.
3. Identificación de defectos.
4. Documentación de bugs.
5. Revisión de resultados.
6. Ejecución de pruebas de regresión luego de correcciones.

---

# 6. Ambiente de Testing

Las pruebas se realizarán en el siguiente entorno:

**Ambiente:** Development

### Navegadores

- Google Chrome
- Mozilla Firefox

### Dispositivos y resoluciones

- Desktop (1920px)
- Tablet (768px)
- Mobile (375px)

---

# 7. Herramientas Utilizadas

Durante el proceso de testing se utilizarán las siguientes herramientas:

- Navegadores Chrome y Firefox
- DevTools del navegador
- GitHub (documentación del proyecto)
- Capturas de pantalla para evidencia de bugs

---

# 8. Criterios de Entrada

El testing comenzará cuando se cumplan las siguientes condiciones:

- El sitio web esté disponible en el ambiente de desarrollo.
- El contenido principal esté implementado.
- Las funcionalidades principales estén accesibles.

---

# 9. Criterios de Salida

El proceso de testing finalizará cuando:

- Todos los casos de prueba hayan sido ejecutados.
- Los bugs detectados estén documentados.
- Se haya generado el reporte final de testing.

---

# 10. Riesgos

Algunos riesgos potenciales durante el testing incluyen:

- Cambios de diseño durante el proceso de pruebas.
- Problemas de compatibilidad entre navegadores.
- Problemas de visualización en distintos dispositivos.

---

# 11. Entregables

Los documentos generados durante el proceso de testing incluyen:

- Test Plan
- Test Cases
- Bug Reports
- Regression Checklist
- Test Execution Report
- Final Test Report

---

# 12. Cronograma de Testing

| Fase | Actividad |
|-----|-----|
| Planificación | Creación del Test Plan |
| Diseño de pruebas | Elaboración de Test Cases |
| Ejecución | Ejecución de casos de prueba |
| Reporte | Documentación de bugs |
| Validación | Pruebas de regresión |
| Cierre | Generación del reporte final |

---