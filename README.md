# Proposito del desafio:

El proyecto tiene como proposito ayudar al Sr Juan a decidir que tienda de su cadena de Alura store debe vender para iniciar un nuevo emprendimiento.

---

## 📌 ¿Qué encontrarás en este repositorio?

Este notebook de Google Colab contiene:

- ✅ ¿Cuánto facturó cada tienda?
- ✅ ¿Qué categorías de productos generan más ingresos?
- ✅ ¿Cuál es la satisfacción promedio de los clientes?
- ✅ ¿Cuáles son los productos más y menos vendidos?
- ✅ ¿Cuánto cuesta el envío en promedio por tienda?

Todo el análisis está realizado en **Python** con la biblioteca **Pandas**, e incluye funciones reutilizables para facilitar la exploración.

---

##  Estructura del análisis  ##

1. **Importación de datos**  
   Carga de cuatro archivos CSV desde un repositorio remoto y primer vistazo a los datos.

2. **Análisis de facturación**  
   Cálculo de los ingresos totales por tienda (suma de la columna `Precio`).

3. **Ventas por categoría**  
   - Conteo de productos vendidos por categoría.  
   - Ingresos generados por cada categoría (con formato monetario).

4. **Calificación promedio**  
   Promedio de calificaciones de los clientes para cada tienda.

5. **Productos más y menos vendidos**  
   Identificación de los 5 productos con mayor y menor cantidad de ventas en cada tienda.

6. **Envío promedio**  
   Cálculo del costo de envío promedio por tienda.

---

##  Resultados destacados  ##

###  Ingresos totales por tienda  ###

| Tienda   | Ingreso total     |
|----------|-------------------|
| Tienda 1 | $1,150,880,400    |
| Tienda 2 | $1,116,343,500    |
| Tienda 3 | $1,098,019,600    |
| Tienda 4 | $1,038,375,700    |

###  Categorías con mayores ingresos (ejemplo Tienda 1) ###

| Categoría         | Ingreso      |
|-------------------|--------------|
| Electrónicos      | $429,493,500 |
| Electrodomésticos | $363,685,200 |
| Muebles           | $187,633,700 |

###  Calificaciones promedio  ##

- Tienda 1: **3.98**
- Tienda 2: **4.04**
- Tienda 3: **4.05**
- Tienda 4: **4.00**

###  Productos más vendidos (Top 1 por tienda)  ###

| Tienda   | Producto                  | Unidades vendidas |
|----------|---------------------------|-------------------|
| Tienda 1 | Microondas                | 60                |
| Tienda 2 | Iniciando en programación | 65                |
| Tienda 3 | Kit de bancas             | 57                |
| Tienda 4 | Cama box                  | 62                |

###  Costo de envío promedio  ###

| Tienda   | Costo promedio |
|----------|----------------|
| Tienda 1 | $26,018.61     |
| Tienda 2 | $25,216.24     |
| Tienda 3 | $24,805.68     |
| Tienda 4 | $23,459.46     |

---

##  Tecnologías utilizadas  ##

- **Python 3**  
- **Pandas**  
- **Google Colab / Jupyter Notebook**

---

##  Cómo usar este proyecto ##

1. Abre el notebook en [Google Colab](https://colab.research.google.com/) o en tu entorno Jupyter local.
2. Ejecuta las celdas en orden para reproducir el análisis.
3. Modifica las funciones o crea nuevas visualizaciones a partir de los DataFrames.


**¡Gracias por visitar este repositorio!** ⭐️ Si te resulta útil, no olvides dejar una estrella.
