# Análisis del catálogo de "Netflix"

## Contexto
Este proyecto contiene el análisis de datos de un catálogo de Netflix, a través de Python. La base contiene datos de las películas por país, año de publicación, duración, género. Este análisis apoyará la estrategia de adquisiciones y contenido original de la plataforma.

## Objetivo
El objetivo es entender la distribución del contenido por país, tipo, duración, clasificaciones, géneros y su evolución en el tiempo.

## Contexto
- El catálogo consta de 8790 títulos, de paises como: Estados Unidos Americanos, India, Reino Unido, Pakistán, México, etc.
- Por país más activo en producción, Estados Unidos lidera con 3240 títulos, seguido por India con: 1057 y Reino Unido con: 638.
- Por año de estreno, la distribución es de la siguiente forma: 2018 con 1146, 2019-2017 con 1030 cada uno, 2020 con 953 y 2016 con 901.
- Los años de estreno con menor cantidad de títulos son: 1961, 1959, 1925, 1966 y 1947.
   
## Resultados

**1. Los títulos que genera mayores rentas son de Estados Unidos**
- El país más activo en producción: **Estados Unidos 3240**, triplicando al país que le sigue: India (1057).
- El nivel de producción de Estados Unidos es similar a la suma de países como: India, Reino Unido, Pakistán, Canadá, Japón, Corea del Sur y Francia.
- El país menos activo fue **Nigeria con 105**, representando 3.2% del país más activo. Por tal motivo se sugiere generar estrategias de difusión para visualización de estos títulos o en su defecto rotarlos en la plataforma.

<img width="598" height="549" alt="image" src="https://github.com/user-attachments/assets/a886fec3-8505-4f35-943f-a34d31d7ac37" />

**2. Titulos por año de estreno**
  - Por año de estreno entre el **2016 y 2020** se estrenaron la mayor cantidad de películas que contiene el catálogo, representando el 57.56% del total.
  - Existe una curva a la alza a partir del año 2005, despegando exponencialmente a partir del 2015. Verificar si se trata de un cambio en las reglas de adquisición de títulos por parte de netflix y dependiendo del movimiento de títulos por época, valorar si pueden adquirise más. 
  - Sin embargo por cantidad neta **el año 2018 es el que más títulos tiene** con 1146, seguido por 2017 y 2019 con 1030 cada uno.

<img width="874" height="466" alt="image" src="https://github.com/user-attachments/assets/dc6a42ce-9771-4390-b674-136b899759d7" />


**3. El género de películas internacionales es el más rentable**
  - El top ten por género se comporta de la siguiente forma: International Movies (2752), Dramas (2426), Comedies (1674), International TV Shows (1349), Documentaries (869), Action & Adventure (859), TV Dramas (762), Independent Movies (756), Children & Family Movies (641) y Romantic Movies (616).
  - Los géneros de **Classic & Cult TV (26) y TV Shows (16)** fueron la que menos rentas tuvieron, en conjunto representando **1.5%** del de Internacional Movies.
  - Se debe valorar el costo-beneficio de que continúen Classic & Cult TV y TV Shows, dependiendo del costo que genera tenerlos dentro de la plataforma.

<img width="748" height="435" alt="image" src="https://github.com/user-attachments/assets/606d8785-0f16-46fd-952c-5d9487f9718c" />


  - ## Contenido de archivos anexos (base datos y Python)
  - Base de datos con preparación de datos
  - Exploración de datos mediante código Python
  - Limpieza de datos por código Python
  - Análisis de datos a través código Python
  - Gráficas del análisis.
