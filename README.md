#BigMart-Sales
En este proyecto vamos a realizar un análisis gráfico de un problema de ventas. Contamos con un dataset de 14204 observaciones y 12 variables que recogen las ventas de 1559 productos en 10 establecimientos de la empresa BigMart en el año 2013. Se puede encontrar el conjunto de datos en [https://zenodo.org/records/6509955](https://zenodo.org/records/6509955).

Descripción de las variables:

* **Item_Identifier**: variable cualitativa nominal indicando el código del artículo.

* **Item_Weight**: variable numérica indicando el peso del artículo. No se nos informa la unidad de medida en la que se han recogido los datos.

* **Item_Fat_Content**: variable cualitativa ordinal indicando el nivel de grasa del artículo. Los posibles valores son `Low Fat`, `Regular`, `low fat`, `LF`, `reg`.

* **Item_Visibility**: valor numérico que indica cómo de visible es un artículo.

* **Item_Type**: variable categórica indicando el tipo de producto: `Dairy`, `Soft Drinks`, `Meat`, `Fruits and Vegetables`, `Household`, `Baking Goods`, `Snack Foods`, `Frozen Foods`, `Breakfast`, `Health and Hygiene`, `Hard Drinks`, `Canned`, `Breads`, `Starchy Foods`, `Others`, `Seafood`.

* **Item_MRP**: variable numérica indicando el MRP (Maximum Retail Price) del producto. 

* **Outlet_Identifier**: variable categórica que contiene el identificador del establecimiento.

* **Outlet_Establishment_Year**: variable cuantitativa discreta indicando el año de inauguración del establecimiento.

* **Outlet_Size**: variable cualtitativa ordinal que muestra el tamaño del establecimiento. Toma los valores `Medium` , `High` y `Small`.

* **Outlet_Location_Type**: variable categórica para indicar la localización del establecimiento: `Tier 1`, `Tier 2`, `Tier 3`.

* **Outlet_Type**: variable categórica que indica el tipo de establecimiento: `Supermarket Type1`, `Supermarket Type2`, `Supermarket Type3`, `Grocery Store`.

* **Item_Outlet_Sales**: variable cuantitativa discreta que indica el número de productos vendidos. 


El objetivo es realizar un análisis exploratorio gráfico para comprender las propiedades de los productos y los establecimientos que pueden desempeñar un papel clave en el aumento de las ventas.
