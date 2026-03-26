# 🧪 QA Testing Practice – Rodolfo Coria

Este repositorio documenta pruebas manuales de software realizadas sobre aplicaciones web desarrolladas por mí, con el objetivo de evaluar su funcionamiento, identificar errores y proponer mejoras.

---

## 🌐 Aplicaciones probadas

### 1. Frontend Store
🔗 https://frontendstore-rc.netlify.app/

### 2. Freelancer Landing Page
🔗 https://freelancer-rodolfocoria.netlify.app/

---

## 🎯 Objetivo

Aplicar fundamentos de QA (Quality Assurance) mediante pruebas funcionales, validación de comportamiento y detección de bugs en aplicaciones web reales.

---

## 🛠️ Herramientas utilizadas

- Navegador web (Firefox Developer Edition)
- Herramientas de desarrollador (DevTools)
- Pruebas manuales

---

## ✅ Casos de Prueba

### Caso 1: Visualización de productos
**Aplicación:** Frontend Store  

**Acción:**  
Cargar la página principal  

**Resultado esperado:**  
Los productos deben mostrarse correctamente  

**Resultado obtenido:**  
Los productos se visualizan correctamente  

**Estado:** ✅ Exitoso  

---

### Caso 2: Diseño responsive
**Aplicación:** Ambas  

**Acción:**  
Visualizar las páginas en diferentes tamaños de pantalla  

**Resultado esperado:**  
El diseño debe adaptarse correctamente  

**Resultado obtenido:**  
Las páginas se adaptan correctamente en diferentes resoluciones  

**Estado:** ✅ Exitoso  

---

### Caso 3: Envío de formulario de contacto
**Aplicación:** Freelancer Landing Page  

**Acción:**  
Completar el formulario y hacer clic en "Enviar"  

**Resultado esperado:**  
El formulario debería enviar la información o mostrar un mensaje de confirmación  

**Resultado obtenido:**  
No ocurre ninguna acción y no hay redirección  

**Estado:** ❌ Fallido  

---

### Caso 4: Agregar producto al carrito
**Aplicación:** Frontend Store  

**Acción:**  
Hacer clic en "Agregar al carrito"  

**Resultado esperado:**  
El producto debería añadirse al carrito  

**Resultado obtenido:**  
No ocurre ninguna acción  

**Estado:** ❌ Fallido  

---

### Caso 5: Navegación del menú
**Aplicación:** Freelancer Landing Page  

**Acción:**  
Hacer clic en los enlaces del menú ("Sobre mí", "Clientes", "Contacto")  

**Resultado esperado:**  
El sistema debería redirigir o hacer scroll a las secciones correspondientes  

**Resultado obtenido:**  
No ocurre ninguna acción  

**Estado:** ❌ Fallido  

---

### Caso 6: Navegación a detalle de producto
**Aplicación:** Frontend Store  

**Acción:**  
Hacer clic en diferentes productos  

**Resultado esperado:**  
Cada producto debería redirigir a su propia página con información específica  

**Resultado obtenido:**  
Todos los productos redirigen a la misma página  

**Estado:** ❌ Fallido  

---

## 🐞 Reporte de Bugs

### Bug 1: Carrito no funcional
**Aplicación:** Frontend Store  

**Descripción:**  
El botón "Agregar al carrito" no realiza ninguna acción al hacer clic  

**Impacto:**  
El usuario no puede realizar compras  

**Severidad:** Alta  
**Prioridad:** Alta  

---

### Bug 2: Formulario sin funcionalidad
**Aplicación:** Freelancer Landing Page  

**Descripción:**  
El botón "Enviar" no ejecuta ninguna acción ni redirige a otra página  

**Impacto:**  
El usuario no puede enviar mensajes de contacto  

**Severidad:** Alta  
**Prioridad:** Alta  

---

### Bug 3: Falta de validación en formulario
**Aplicación:** Freelancer Landing Page  

**Descripción:**  
El formulario no valida campos obligatorios ni formato de correo  

**Impacto:**  
Se pueden ingresar datos inválidos  

**Severidad:** Media  
**Prioridad:** Alta  

---

### Bug 4: Enlaces de navegación no funcionales
**Aplicación:** Freelancer Landing Page  

**Descripción:**  
Los enlaces del menú de navegación no redirigen ni hacen scroll a ninguna sección  

**Impacto:**  
El usuario no puede navegar dentro del sitio correctamente  

**Severidad:** Media  
**Prioridad:** Alta  

---

### Bug 5: Redirección incorrecta de productos
**Aplicación:** Frontend Store  

**Descripción:**  
Todos los productos redirigen a la misma página, mostrando el mismo contenido  

**Impacto:**  
El usuario no puede visualizar información específica de cada producto  

**Severidad:** Alta  
**Prioridad:** Alta  

---

## 📸 Evidencias

### Carrito no funcional
![Carrito](evidencias/carrito-boton)

### Formulario sin envío
![Formulario](evidencias/formulario-envio)

### Navegación sin funcionalidad
![Navegación](evidencias/navegacion-menu)

### Redirección incorrecta de productos
![Productos](evidencias/producto-redireccion)

---

## 📌 Conocimientos aplicados

- Pruebas funcionales  
- Identificación de bugs  
- Validación de formularios  
- Análisis de navegación  
- Evaluación de experiencia de usuario (UX)  

---

## 🚀 Próximos pasos

- Implementar pruebas automatizadas  
- Uso de Postman para pruebas de APIs  
- Mejora de cobertura de pruebas  

---
