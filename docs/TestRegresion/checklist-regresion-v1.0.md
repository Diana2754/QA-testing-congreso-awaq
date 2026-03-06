# Regression Execution – v1.0

## Información General

- **Versión:** 1.0  
- **Tipo de ejecución:** Primera ejecución del checklist de regresión  
- **Tester:** Diana Alali
- **Fecha:** 17/03/2025 
- **Ambiente:** Dev 
- **Resultado general:** Fallido

---

## Resumen de resultados

| Área | Resultado |
|-----|-----|
| Navegación | ✅ Aprobado |
| UI / Integridad visual | ⚠️ Parcial |
| Responsive | ❌ Fallido |
| Formularios | ❌ Fallido |
| Cross-browser | ✅ Aprobado |
| Performance | ✅ Aprobado |
| Accesibilidad | ⚠️ Parcial |

---

## Bugs detectados

### BUG-001 – Menú se superpone en mobile
**Severidad:** Alta  
**Dispositivo:** Mobile (375px)

**Descripción:**  
Al abrir el menú hamburguesa en mobile, el menú desplegable se superpone con el contenido de la página.

**Resultado esperado:**  
El menú debe desplegarse correctamente sin superponer elementos.

**Evidencia:**  
Ver imagen en `/assets/bug-menu-mobile.png`

---


### BUG-002 – Texto cortado en sección "Nosotros"
**Severidad:** Media

**Descripción:**  
En tablet (768px) el párrafo principal aparece cortado.

---

### BUG-003 – Texto cortado en sección "Nosotros"
**Severidad:** Media

**Descripción:**  
En tablet (768px) el párrafo principal aparece cortado.

---
## Conclusión

La versión **no aprueba regresión**.  
Se reportan los bugs al equipo de desarrollo para corrección.