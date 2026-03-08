# 📊 Challenge 1: Análisis de Datos - Alura Store 🚀

Este repositorio contiene la resolución del primer desafío de Data Science de **Alura Latam**. El objetivo principal es ayudar al **Sr. Juan**, dueño de la cadena Alura Store, a decidir qué tienda debe vender basándose en el rendimiento operativo y financiero.

---

## 📝 Escenario del Proyecto
El Sr. Juan planea iniciar un nuevo emprendimiento y necesita capital. Para ello, debemos analizar el desempeño de sus 4 tiendas e identificar la **menos eficiente**.

El análisis se centra en:
* **Ingresos Totales:** Cuál tienda genera menor rentabilidad.
* **Satisfacción del Cliente:** Análisis de las calificaciones promedio.
* **Desempeño de Productos:** Identificación de categorías y productos con baja rotación.
* **Eficiencia Logística:** Impacto de los costos de envío.
* **Análisis Geográfico:** Distribución de las ventas según latitud y longitud.

---

## 🛠️ Tecnologías y Librerías Utilizadas
* **Python** (Google Colab)
* **Pandas**: Manipulación y limpieza de datos.
* **Matplotlib / Seaborn**: Visualización de datos y gráficos estadísticos.
* **Folium**: Mapeo geoespacial interactivo (Extra Challenge).

---

## 📂 Estructura del Análisis

### 1. Carga y Procesamiento
Se integraron los datos de las 4 tiendas (`tienda_1`, `tienda_2`, `tienda_3`, `tienda_4`) para realizar una comparación equitativa.

### 2. Visualización de Datos
Se generaron gráficos específicos para responder a las preguntas de negocio:
* **Gráficos de Barras:** Para comparar ingresos y volumen de ventas.
* **Gráficos de Líneas/Puntos:** Para monitorear la satisfacción del cliente.
* **Gráficos de Dispersión:** Para analizar la relación entre costos de envío y ventas.

### 3. Análisis Geográfico (Challenge Extra)
Utilizando las coordenadas `lat` y `lon`, se mapeó la concentración de ventas para entender si la ubicación geográfica influye en los altos costos de envío observados en ciertas sucursales.

---

## 💡 Conclusión y Recomendación Final

Tras el análisis de datos, se recomendó la venta de la **Tienda 4** debido a los siguientes hallazgos:
1. **Baja Rentabilidad:** Es la sucursal con los ingresos totales más bajos.
2. **Problemas de Logística:** Presenta el costo de envío promedio más alto, lo que desincentiva la compra.
3. **Mala Calificación:** Los clientes han otorgado los promedios de satisfacción más bajos en comparación con las otras tiendas.

---

## 📁 Contenido del Repositorio
* `AluraStoreLatam.ipynb`: Notebook de Google Colab con todo el código y análisis.
* `README.md`: Documentación del proyecto.

---

## 🚀 Cómo usar este proyecto
1. Abre el archivo `.ipynb` en **Google Colab**.
2. Asegúrate de cargar los archivos CSV de las 4 tiendas en el entorno de ejecución.
3. Ejecuta las celdas secuencialmente para observar el proceso de análisis y los gráficos resultantes.

---

**Autor:** [Janampag](https://github.com/janampag)
