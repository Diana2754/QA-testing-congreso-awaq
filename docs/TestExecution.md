# Test Execution – v1.0

## Información General

- **Proyecto:** Congreso Internacional de Organizaciones Ambientales
- **Tester:** Diana Alali
- **Fecha:** 07/03/2025
- **Ambiente:** Development
- **Tipo de ejecución:** Primera ejecución de casos de prueba

---

# Resultados de Ejecución

| Test Case ID | Descripción | Resultado | Observaciones |
|---------------|-------------|-----------|---------------|
| TC-01 | Verificar que el logo redirige al inicio |  Fallido | El logo no redirige al home (BUG-005) |
| TC-02 | Verificar funcionamiento del menú principal |  Aprobado | Navegación correcta |
| TC-03 | Verificar funcionamiento de enlaces del footer |  Aprobado | Todos los enlaces funcionan |
| TC-04 | Verificar visibilidad del hover del menú |  Fallido | Hover casi imperceptible (BUG-004) |
| TC-05 | Verificar visualización correcta del logo |  Fallido | Logo desactualizado (BUG-005) |
| TC-06 | Verificar visualización del carrusel |  Aprobado | Se visualiza correctamente |
| TC-07 | Verificar navegación manual del carrusel |  Aprobado | Funcionamiento correcto |
| TC-08 | Verificar visualización sección "Nosotros" |  Fallido | Texto aparece cortado en tablet (BUG-002) |
| TC-09 | Verificar menú en mobile |  Fallido | Menú se superpone al contenido (BUG-001) |
| TC-10 | Verificar visualización del texto en tablet |  Fallido | Texto no se adapta correctamente (BUG-003) |
| TC-11 | Verificar adaptación del carrusel en mobile |  Aprobado | Se adapta correctamente |
| TC-12 | Verificar funcionamiento del botón de donación |  Fallido | No redirige correctamente (BUG relacionado) |
| TC-13 | Verificar animación de loading |  Fallido | Loading corresponde a versión 2024 (BUG-006) |
| TC-14 | Verificar visualización en Chrome |  Aprobado | Sin problemas |
| TC-15 | Verificar visualización en Firefox |  Parcial | Problema en sección "Nosotros" |

---

# Resumen de Resultados

| Resultado | Cantidad |
|-----------|----------|
| Aprobados | 7 |
| Fallidos | 7 |
| Parciales | 1 |

---

# Bugs Asociados

Durante la ejecución se detectaron los siguientes defectos:

| Bug ID | Descripción | Severidad |
|-------|-------------|-----------|
| BUG-001 | Menú se superpone en mobile | Alta |
| BUG-002 | Texto cortado en sección "Nosotros" | Media |
| BUG-003 | Problema de visualización en Firefox | Media |
| BUG-004 | Hover del menú poco visible | Baja |
| BUG-005 | Logo del congreso desactualizado | Alta |
| BUG-006 | Loading pertenece al diseño del congreso 2024 | Baja |

---

# Conclusión

La versión actual **no aprueba la ejecución de pruebas**, ya que se detectaron múltiples defectos funcionales y visuales.

Se recomienda corregir los bugs reportados y realizar **una nueva ejecución de pruebas de regresión** para validar las correcciones implementadas.