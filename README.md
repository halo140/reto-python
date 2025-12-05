# ?? An芍lisis de Facturaci車n - Cadena de Tiendas Retail

## ?? Descripci車n del Proyecto

Este proyecto es parte de un desaf赤o de Data Science donde actuamos como analistas de datos para una cadena de comercio. El objetivo principal fue analizar los datos de **4 tiendas distintas** para ayudar al due?o (Sr. Juan) a tomar una decisi車n estrat谷gica importante: **identificar cu芍l tienda tiene el menor rendimiento y deber赤a ser vendida.**

Utilizando Python, procesamos archivos CSV con miles de transacciones para extraer insights sobre ventas, satisfacci車n del cliente y log赤stica.

## ?? Tecnolog赤as Utilizadas

El an芍lisis fue realizado en **Google Colab** utilizando las siguientes librer赤as:

* **Python 3**
* **Pandas:** Para la manipulaci車n y limpieza de los datos (DataFrames).
* **Matplotlib & Seaborn:** Para la generaci車n de gr芍ficos y visualizaci車n de datos.

## ?? Estructura del An芍lisis

El c車digo recorre los siguientes pasos clave:

1. **Carga de Datos:** Importaci車n de 4 datasets (CSV) desde un repositorio remoto.
2. **Limpieza y Agrupaci車n:** Organizaci車n de las tiendas en una estructura iterable para evitar repetir c車digo.
3. **C芍lculo de KPIs:**
    * ?? Ingresos Totales por tienda.
    * ?? Ventas por Categor赤a.
    * ? Calificaci車n Promedio de satisfacci車n.
    * ?? Costo Promedio de Env赤o.
    * ?? Productos m芍s y menos vendidos.
4. **Visualizaci車n:** Gr芍ficos de barras y dispersi車n para comparar el rendimiento.
5. **Informe Final:** Recomendaci車n estrat谷gica basada en datos.

## ?? Hallazgos Principales

Despu谷s de procesar los datos, llegamos a las siguientes conclusiones:

* La **Tienda 1** es la l赤der indiscutible en ingresos, superando los $1,150 millones.
* La categor赤a de **Muebles** es el producto estrella en todas las sucursales.
* Existe una discrepancia entre ventas y satisfacci車n: la tienda que m芍s vende es la que tiene la calificaci車n m芍s baja.

### ?? Conclusi車n

El an芍lisis sugiere que la **Tienda 4** es la candidata ideal para la venta, ya que presenta el **menor volumen de facturaci車n** ($1,038 millones) y no demuestra ventajas competitivas significativas frente a las otras sucursales.

## ??? C車mo ejecutar este proyecto

1. Clona este repositorio.
2. Abre el archivo `.ipynb` en Google Colab o Jupyter Notebook.
3. Aseg迆rate de tener instaladas las librer赤as necesarias:
```bash
    pip install pandas matplotlib seaborn
```
4. Ejecuta las celdas en orden para ver el an芍lisis paso a paso.

---

*Desarrollado como parte de un reto de an芍lisis de datos con Python.*