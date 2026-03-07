# Final Test Report – Congreso Internacional de Organizaciones Ambientales

## Información General

- **Proyecto:** Web del Congreso Internacional de Organizaciones Ambientales  
- **Tipo de proyecto:** Sitio web informativo  
- **Tester:** Diana Alali  
- **Fecha del reporte:** 02/02/2025  
- **Ambiente testeado:** Development  
- **Navegadores utilizados:** Chrome, Firefox  

### Dispositivos evaluados

- Desktop (1920px)  
- Tablet (768px)  
- Mobile (375px)

---

# Objetivo del Testing

El objetivo de las pruebas fue verificar el correcto funcionamiento del sitio web, su integridad visual, usabilidad y comportamiento responsive en diferentes dispositivos y navegadores.

Se buscó asegurar que todos los componentes del sitio funcionen correctamente antes de su liberación.

---

# Alcance del Testing

Las pruebas incluyeron los siguientes componentes del sitio:

- Header y menú de navegación
- Logo del congreso
- Carrusel de imágenes
- Sección "Nosotros"
- Información del evento
- Cronograma de actividades
- Botón de donación (PayPal)
- Footer y enlaces institucionales
- Adaptabilidad responsive
- Integridad visual del sitio

---

# Tipos de Testing Realizados

Durante el proceso de QA se realizaron los siguientes tipos de pruebas:

- Testing funcional
- Testing de interfaz de usuario (UI)
- Testing de experiencia de usuario (UX)
- Testing responsive
- Testing cross-browser
- Testing de regresión

---

# Historial de Ejecución de Pruebas

Durante el proceso de testing se realizaron **tres ciclos de ejecución**:

| Ejecución | Resultado | Observaciones |
|----------|-----------|---------------|
| Regression v1 | ❌ Fallido | Se detectaron 6 bugs |
| Regression v2 | ⚠️ Parcial | Se corrigieron defectos críticos |
| Regression v3 | ✅ Aprobado | No se detectaron nuevos defectos |

---

# Bugs Detectados y Corrección

Durante la primera ejecución se identificaron los siguientes defectos:

| ID | Descripción | Severidad | Estado |
|----|-------------|-----------|--------|
| BUG-001 | Menú se superpone en mobile | Alta | ✅ Resuelto |
| BUG-002 | Texto cortado en sección "Nosotros" (tablet) | Media | ✅ Resuelto |
| BUG-003 | Texto cortado en sección "Nosotros" en Firefox | Media | ✅ Resuelto |
| BUG-004 | Hover del menú poco visible | Baja | ✅ Resuelto |
| BUG-005 | Logo del congreso desactualizado | Alta | ✅ Resuelto |
| BUG-006 | Loading pertenece al diseño del congreso 2024 | Baja | ✅ Resuelto |

---

# Resultados Finales

Luego de aplicar las correcciones y ejecutar **la tercera instancia de pruebas de regresión**, se verificó que:

- Los bugs reportados fueron corregidos.
- No se detectaron nuevos defectos.
- El sitio mantiene su integridad funcional y visual.

---

# Conclusión

La versión actual del sitio **aprueba el proceso de testing** luego de la tercera ejecución de pruebas de regresión.

El sitio cumple con los criterios de calidad establecidos y se encuentra **apto para su liberación**.

---

# Recomendaciones

Para futuras versiones se recomienda:

- Continuar realizando pruebas de regresión ante cualquier cambio de diseño o funcionalidad.
- Mantener actualizada la identidad visual del evento.
- Evaluar periódicamente la experiencia de usuario en distintos dispositivos.

---