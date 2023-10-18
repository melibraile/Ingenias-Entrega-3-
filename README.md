<h1 align="center"> Entrega 3</h1>
<h1 align="center"> Proyecto Netflix - grupo 4 </h1>


## Integrantes ✒️
* **Mariela Abrego**
* **Melisa Braile** 
* **Tania Damiani**
* **Mariana Grau**
* **Micaela Melian**

## Descripción de la plataforma Netflix

Netflix es un servicio de streaming que te ofrece una amplia gama de películas, series y documentales de alta calidad, disponibles en prácticamente cualquier dispositivo conectado a internet.
El usuario puede disfrutar de todo lo que desee ver, sin restricciones ni interrupciones publicitarias, a un precio accesible. Además, todas las semanas se ingresan nuevos contenidos a la plataforma. 
La propuesta de valor es: disfruta de tus contenidos cuándo y dónde quieras. Es posible iniciar sesión desde cualquier dispositivo conectado a internet, ya sea, computadoras, smart TVs, smartphones, tables, reproductores multimedia y consolas de videojuegos. Además contratando el servicio es posible descargar y ver de forma offline el contenido en dispositivos IOS, Android o la aplicación para Windows 10. 
Netflix cuenta con un extenso catálogo que incluye películas, series, documentales, animes y producciones originales galardonadas. 

Fuente: www.netflix.com

## Objetivo 📌
A partir de los datos históricos, buscamos predecir cuántas semanas va a estar un título top ten en Netflix  en las diferentes regiones, teniendo el cuenta el género, el content type y el tipo de estación a la que pertenecen


## Diccionario de Datos 📄

*  netflix_modelo.xlsx: dataset utilizado para los modelos

| Features  | Descripcion |
| ------------- | ------------- |
| region  | indica continente en el cual se proyecta la serie o película  |
| country_name | nombre del país en el cual se proyecta la serie o película  |
| country_iso2  | código ISO del país (Código de dos letras para identificar países según la norma ISO 3166-1)  |
| week | semana en la cuál la película o serie se encontró en el TOP10 |
| category  | indica la clasificación de los títulos en Serie o Película <li>**Movie**</li><li>**Series**</li>   | 
| weekly_rank  |indica la cantidad de semanas que el título estuvo en el TOP10  |
| show_title  | nombre de la serie o película |
| season_title | para el caso de las series indica el título de cada temporada  |
| cumulative_weeks_in_top_10  | cantidad de semanas acumuladas que el título estuvo en el TOP10  |
| Realease Year  | año de lanzamiento de la serie o película |
| Genre | género que identifica la serie o película | 


* entorno.xlsx: varios datases con información adicional al dataset principal. Estos dataset aportaron valor al análisis inicial de los datos.

market_cap: datos de distintas plataformas del mundo
| Features  | Descripcion |
| ------------- | ------------- |
| Rank  | ranking  |
| Name | nombre de la plataforma  |
| Symbol  | simbolo que indica la plataforma  |
| marketcap  |  métrica financiera que indica el tamaño o valor de la empresa |
| price (USD)  |  precio |
|country  |  pais de origen de la compañía |

global_users: datos de los usuarios suscriptos a la plataforma Netflix
| Features  | Descripcion |
| ------------- | ------------- |
| Year  | año  |
| Netflix Subscribers  | cantidad de suscriptores  |
|Unidad |  unidad de medida |


suscribers_by_region: datos de los suscriptores por región
| Features  | Descripcion |
| ------------- | ------------- |
| Region  | año  |
| Paid_suscribers  | cantidad de suscriptores  |


revenue_years: datos de ingreso monetario por año
| Features  | Descripcion |
| ------------- | ------------- |
|Year  | año |
|Revenue  | monto |
|Unidad  | unidad monetaria |


 



