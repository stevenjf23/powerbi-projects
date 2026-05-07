
# Dashboard de Gestión de Ventas: Análisis de Insumos y Rendimiento Comercial

## 📝 Descripción del Proyecto
Este dashboard de Power BI proporciona un análisis detallado del rendimiento de ventas basado en la **Suma de Monto**. El reporte permite desglosar los ingresos por tipo de producto y evaluar el desempeño individual de la fuerza de ventas. 

El panel está diseñado para transformar datos crudos de múltiples fuentes en información accionable, permitiendo identificar qué categorías (como Grifería o Herramientas) tienen mayor peso financiero y qué asesores lideran dichas categorías.

## 🖼️ Vista Previa del Análisis
![Gráfico de Ventas por Descripción](imagen.png)
*Gráfico de columnas apiladas mostrando la distribución de montos por categoría y vendedor.*

## 📂 Orígenes de Datos e Integración
Este proyecto destaca por su arquitectura de datos híbrida, utilizando tres métodos principales de obtención en Power BI:

1.  **Google Sheets:** Conexión en la nube para extraer datos transaccionales actualizados en tiempo real por el equipo de ventas.
2.  **Carpeta Local/Compartida:** Implementación de un proceso ETL (Extract, Transform, Load) para consolidar automáticamente múltiples archivos históricos (CSV/Excel) depositados en un directorio.
3.  **Introducción Manual de Datos:** Creación de tablas internas mediante la opción "Especificar datos" para definir objetivos de venta, metas mensuales y parámetros de referencia.

## 🚀 Características Técnicas
* **Conectividad Multi-fuente:** Integración fluida de datos locales y en la nube.
* **Visualizaciones Dinámicas:** Uso de gráficos de columnas apiladas para comparar el aporte de cada vendedor dentro de cada categoría de producto.
* **Segmentación Comercial:** Análisis específico para los asesores:
    * Jorge Luis Ertel
    * José Manuel Moreno
    * Patricia Belén Carrara
    * Sonya Teresa Mayllard

## 🛠️ Categorías de Productos Analizadas
El reporte segmenta la facturación en los siguientes sets de insumos:
* **Set de Juntas y Fijación**
* **Set de Grifería**
* **Set Eléctrico**
* **Set de Adhesivos y Pinturas**
* **Set de Herramientas**

## 🔧 Requisitos para la Réplica
Para ejecutar o editar este archivo `.pbix`, se requiere:
* Power BI Desktop (Versión más reciente recomendada).
* Credenciales de acceso a la cuenta de Google (para el origen de Google Sheets).
* Estructura de carpetas local idéntica a la configurada en los parámetros del origen de datos.
