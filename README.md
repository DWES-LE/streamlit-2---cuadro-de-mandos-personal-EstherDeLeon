# 📈 Cuadro de mandos personal 📊
 
​Encuentra la aplicación desplegada en el siguiente repositorio:
https://estherdeleon-streamlit-2---cuadro-de-mandos-personal-app-sbh3y5.streamlit.app/

## Objetivo
Diseño de un cuadro de mandos personal para visualización e interacción con un conjunto de datos.

## Los datos
Los datos que estaré utilizando son de la compañía Airbnb.

## Búsqueda de los datos
El dataset que voy a usar lo voy a sacar de la web Kaggle.

## Documentación de los datos


Los datos que voy a usar son de la empresa Airbnb, mas concretamente de sus datos en la ciudad de New York, he conseguido estos datos mediante un dataset en la web de Keaggle.
Los campos que hay en este dataset son:
id, name, host_id, neighbourhood, roomtype, price, number_of_reviews, availability ,etc. 

Los valores de estos campos son mayoritariamente numéricos y de texto.
Basicamente son los datos de sus propiedades en New York, los barrios donde están, la disponibilidad que tienen, los precios que manejan...
# 




## Carga y análisis de conjunto de dato con pandas
Despues de cargar los datos, he hecho varios print para ver los campos y las columnas del csv.

## Visualización de los datos
He preparado visualizaciones con ptl y con el mismo streamlit.

## Diseña la interacción que van a tener tus datos
He sacado la tabla completa y despues he creado tres selectbox que sacan por pantalla tablas filtradas según la seleccion que hagas en cada caso.

Despúes he creado varios gráficos y algun grafico de porcentaje que hace que los datos sean más sencillos de visualizar.

## Prepara la aplicación (cuadro de mandos) con Streamlit
Para probar la aplicación una vez clonado el repositorio: 

```bash
git clone https://github.com/DWES-LE/streamlit-2---cuadro-de-mandos-personal-EstherDeLeon.git
```
Y hechos los cambios, he ejecutado el siguiente comando:
```bash

 streamlit run app.py

```



