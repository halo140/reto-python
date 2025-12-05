# 📊 Análisis de Facturación - Cadena de Tiendas Retail

## 📝 Descripción del Proyecto

Este proyecto es parte de un desafío de Data Science donde actuamos como analistas de datos para una cadena de comercio. El objetivo principal fue analizar los datos de **4 tiendas distintas** para ayudar al dueño (Sr. Juan) a tomar una decisión estratégica importante: **identificar cuál tienda tiene el menor rendimiento y debería ser vendida.**

Utilizando Python, procesamos archivos CSV con miles de transacciones para extraer insights sobre ventas, satisfacción del cliente y logística.

## 🚀 Tecnologías Utilizadas

El análisis fue realizado en **Google Colab** utilizando las siguientes librerías:

* **Python 3**
* **Pandas:** Para la manipulación y limpieza de los datos (DataFrames).
* **Matplotlib & Seaborn:** Para la generación de gráficos y visualización de datos.

## 📂 Estructura del Análisis

El código recorre los siguientes pasos clave:

1. **Carga de Datos:** Importación de 4 datasets (CSV) desde un repositorio remoto.
2. **Limpieza y Agrupación:** Organización de las tiendas en una estructura iterable para evitar repetir código.
3. **Cálculo de KPIs:**
   * 💰 Ingresos Totales por tienda.
   * 📦 Ventas por Categoría.
   * ⭐ Calificación Promedio de satisfacción.
   * 🚚 Costo Promedio de Envío.
   * 🏆 Productos más y menos vendidos.
4. **Visualización:** Gráficos de barras y dispersión para comparar el rendimiento.
5. **Informe Final:** Recomendación estratégica basada en datos.

## 📈 Hallazgos Principales

Después de procesar los datos, llegamos a las siguientes conclusiones:

* La **Tienda 1** es la líder indiscutible en ingresos, superando los $1,150 millones.
* La categoría de **Muebles** es el producto estrella en todas las sucursales.
* Existe una discrepancia entre ventas y satisfacción: la tienda que más vende es la que tiene la calificación más baja.

### 🏁 Conclusión

El análisis sugiere que la **Tienda 4** es la candidata ideal para la venta, ya que presenta el **menor volumen de facturación** ($1,038 millones) y no demuestra ventajas competitivas significativas frente a las otras sucursales.

## 🛠️ Cómo ejecutar este proyecto

1. Clona este repositorio.
2. Abre el archivo `.ipynb` en Google Colab o Jupyter Notebook.
3. Asegúrate de tener instaladas las librerías necesarias:
```bash
   pip install pandas matplotlib seaborn
```
4. Ejecuta las celdas en orden para ver el análisis paso a paso.

---

*Desarrollado como parte de un reto de análisis de datos con Python.*