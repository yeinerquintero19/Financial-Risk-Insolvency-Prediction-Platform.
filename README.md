# RiskVision AI — Standalone Web Application

Plataforma SaaS de **Inteligencia Financiera** y **Predicción de Riesgo de Quiebra** diseñada con estética empresarial de alto nivel (inspirada en Stripe, Linear y Vercel).

> 🚀 **Ejecución Instantánea (Zero-Config)**: Esta versión ha sido empaquetada en una aplicación web ejecutable en un único archivo (`index.html`). No requiere servidores locales, Docker, `npm install` ni configuración de bases de datos.

---

## ⚡ ¿Cómo abrir la aplicación en tu computadora?

1. Ve a la carpeta del proyecto `c:\Users\RYZEN\Downloads\Restaurante`.
2. Haz **doble clic** sobre el archivo **`index.html`** (o arrástralo a tu navegador favorito: Chrome, Edge, Firefox, Safari).
3. ¡Listo! La plataforma se abrirá de inmediato con datos dinámicos, gráficos interactivos, chat con IA y simulador predictivo.

---

## 🌐 ¿Cómo subirla a GitHub y Vercel en 1 minuto?

### **Opción 1: Despliegue en Vercel (Recomendado)**
1. Crea un repositorio en GitHub e sube esta carpeta.
2. Ve a [Vercel](https://vercel.com/) e inicia sesión.
3. Haz clic en **"Add New Project"** e importa tu repositorio de GitHub.
4. Vercel detectará automáticamente el archivo `vercel.json` y `index.html` y lo publicará en un enlace público HTTPS instantáneo.

### **Opción 2: GitHub Pages (Gratuito)**
1. Sube el proyecto a tu repositorio de GitHub.
2. Ve a la pestaña **Settings** de tu repositorio en GitHub.
3. En la sección **Pages**, selecciona la rama `main` y guarda.
4. Tu sitio estará disponible públicamente en `https://tu-usuario.github.io/tu-repositorio/`.

---

## 📊 Funcionalidades Incluidas en la App

1. **Dashboard Ejecutivo & Semáforo de Riesgo**:
   - Medidor radial interactivo con porcentaje de riesgo de insolvencia (Bajo, Medio, Alto).
   - Cálculo del score **Altman Z-Score** en tiempo real.
   - Indicadores KPI (Ventas, Utilidad Neta, Liquidez Corriente, Ratio de Endeudamiento, Margen Neto).
   - Gráficas interactivas con Chart.js (Evolución de Ingresos vs Gastos, Distribución de Gastos, Radar de Salud Financiera).

2. **Chat IA Financiero (Estilo ChatGPT)**:
   - Chat interactivo que responde preguntas en lenguaje natural ("¿Mi empresa está en riesgo?", "¿Qué gastos reducir?", "¿Si las ventas caen 15%?").
   - Respuestas generadas en base a los registros contables reales de la empresa seleccionada.

3. **Simulador de Escenarios Predictivos**:
   - Deslizadores en tiempo real para simular caídas de ventas, inflación en costos o recortes de gastos.
   - Recálculo instantáneo del nuevo porcentaje de riesgo, margen de utilidad y meses de runway de caja restante.

4. **Gestor & Recalculador de Datos Financieros**:
   - Formulario para actualizar Ingresos, Gastos, Activo Circulante, Pasivo Circulante y Deudas, recalculando inmediatamente todo el motor de scoring.

5. **Informe de Auditoría Ejecutiva**:
   - Generador de reporte descargable/imprimible en PDF con un clic.
