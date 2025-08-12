# Challenge_Alura_Store: Análisis para decidir qué tienda vender — Caso Juan

## Descripción
Este proyecto ayuda al señor Juan a evaluar el desempeño de cuatro tiendas para decidir cuál vender y así invertir en un nuevo negocio. Se analizan cinco aspectos clave: facturación total, categorías más populares, calificaciones promedio de clientes, productos más y menos vendidos, y costos promedio de envío.

## Datos utilizados
Se trabajó con cuatro DataFrames (uno por tienda) que contienen información de ventas durante un periodo determinado. Cada DataFrame tiene 2358-2359 registros con las siguientes columnas principales:
- Producto
- Categoría del Producto
- Precio
- Costo de envío
- Fecha de Compra (formato dd/mm/yyyy)
- Calificación del cliente
- Otros datos relacionados con venta y ubicación

## Análisis realizados
1. **Facturación total por tienda:** cálculo del total vendido por tienda.
2. **Categorías más vendidas:** identificación de las 5 categorías más populares en cada tienda.
3. **Calificación promedio:** promedio de evaluación de clientes por tienda.
4. **Productos más y menos vendidos:** análisis de los productos con mayor y menor cantidad de ventas.
5. **Costo promedio de envío:** promedio del costo de envío desde la tienda al cliente.

## Conclusión

Al analizar los datos de facturación, popularidad de categorías, evaluación de clientes, productos más y menos vendidos, y costos de envío, se concluye lo siguiente:

### 1. Facturación total  
La **Tienda 4** presenta la menor facturación anual desde 2021 hasta la fecha, con un total acumulado inferior a las otras tres tiendas:

| Año  | Tienda 1 | Tienda 2 | Tienda 3 | Tienda 4 |
|-------|----------|----------|----------|----------|
| 2020  | 368,933  | 320,466  | 321,707  | 330,847  |
| 2021  | 362,120  | 351,215  | 362,954  | 347,823  |
| 2022  | 316,565  | 358,226  | 350,438  | 302,221  |
| 2023  | 103,260  | 86,434   | 62,919   | 57,482   |
| **Total** | 1,150,880 | 1,116,343 | 1,098,019 | 1,038,375 |

---

### 2. Popularidad por categoría  
Las categorías más vendidas en todas las tiendas son **Muebles** y **Electrónicos**. Sin embargo, la Tienda 4 tiene bajas ventas en **Electrodomésticos**, que es la categoría con mayor precio promedio y, por tanto, mayor rentabilidad.

---

### 3. Evaluación de clientes  
La Tienda 4 tiene una evaluación promedio general bueno (4.00), aunque es la segunda peor entre las cuatro tiendas, a pesar de su mejora reciente.

---

### 4. Productos más y menos vendidos  
En general, el producto menos vendido en cada tienda tiene menor precio que el más vendido. Sin embargo, en la Tienda 4 el producto menos vendido tiene un precio considerablemente más alto que el más vendido, lo que reduce su rentabilidad.

---

### 5. Costo promedio de envío  
La Tienda 4 tiene el costo promedio de envío más bajo, lo cual es positivo, pero podría indicar que los productos de mayor valor y mayor costo de envío se venden menos, afectando la rentabilidad.

---

## Recomendación final

**La Tienda 4 es la menos rentable y, por tanto, la que debería considerar vender el señor Juan para invertir en un nuevo negocio.**


## Herramientas utilizadas
- Python (Pandas, Matplotlib/Seaborn)
- Google Colab

---

