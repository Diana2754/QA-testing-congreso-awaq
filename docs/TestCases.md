# Test Cases – Congreso Internacional de Organizaciones Ambientales

## Información General

- **Proyecto:** Web del Congreso Internacional de Organizaciones Ambientales
- **Tester:** Diana Alali
- **Tipo de testing:** Funcional / UI / UX / Responsive
- **Ambiente:** Development

---

# Test Cases

| ID | Módulo | Descripción | Precondición | Pasos | Resultado Esperado |
|----|------|-------------|-------------|------|--------------------|
| TC-01 | Navegación | Verificar que el logo redirige al inicio | Usuario en cualquier sección | 1. Hacer clic en el logo | El usuario es redirigido a la página principal |
| TC-02 | Navegación | Verificar funcionamiento del menú principal | Sitio cargado | 1. Hacer clic en cada opción del menú | Cada opción redirige a su sección correspondiente |
| TC-03 | Navegación | Verificar funcionamiento de enlaces del footer | Sitio cargado | 1. Hacer clic en los enlaces del footer | Los enlaces redirigen correctamente |
| TC-04 | UI | Verificar visibilidad del estado hover en el menú | Sitio cargado en desktop | 1. Pasar el cursor sobre cada opción del menú | El estado hover debe ser claramente visible |
| TC-05 | UI | Verificar visualización correcta del logo del congreso | Sitio cargado | 1. Observar el header | El logo corresponde a la versión actual del evento |
| TC-06 | UI | Verificar visualización del carrusel | Sitio cargado | 1. Observar carrusel | Las imágenes se muestran correctamente |
| TC-07 | Funcional | Verificar navegación manual del carrusel | Sitio cargado | 1. Hacer clic en controles del carrusel | Las imágenes cambian correctamente |
| TC-08 | Contenido | Verificar visualización de sección "Nosotros" | Sitio cargado | 1. Ir a la sección "Nosotros" | El texto se visualiza completo |
| TC-09 | Responsive | Verificar visualización del menú en mobile | Resolución mobile | 1. Abrir menú hamburguesa | El menú se despliega sin superponerse |
| TC-10 | Responsive | Verificar visualización de texto en tablet | Resolución tablet | 1. Ir a sección "Nosotros" | El texto no aparece cortado |
| TC-11 | Responsive | Verificar adaptación del carrusel en mobile | Resolución mobile | 1. Visualizar carrusel | El carrusel se adapta correctamente |
| TC-12 | Funcional | Verificar funcionamiento del botón de donación | Sitio cargado | 1. Hacer clic en botón de donación | Redirige correctamente a PayPal |
| TC-13 | UI | Verificar animación de loading | Recargar página | 1. Refrescar página | El loading corresponde al diseño actual del evento |
| TC-14 | Cross Browser | Verificar visualización en Chrome | Abrir sitio en Chrome | 1. Navegar por el sitio | El sitio se visualiza correctamente |
| TC-15 | Cross Browser | Verificar visualización en Firefox | Abrir sitio en Firefox | 1. Navegar por el sitio | El sitio se visualiza correctamente |

---

# Observaciones

Los resultados de la ejecución de estos casos de prueba se documentan en el archivo de **Test Execution** correspondiente.