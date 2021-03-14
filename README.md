

## Datos de los Compendios Estadísticos de la Dirección del Trabajo en formato amigable

Proyecto colaborativo de [Repositorio de Estadísticas Sindicales](https://repositoriosindical.netlify.app/).

La Dirección del Trabajo publica interesante información estadística sobre sindicatos, negociaciones colectivas y huelgas en sus [compendios estadísticos](https://www.dt.gob.cl/portal/1629/w3-propertyvalue-22777.html) para los años 1990-2019. Sin embargo, las tablas se encuentran en formato `pdf`, lo que dificulta su uso y análisis. Con el objeto de hacerle la vida más fácil a los y las colegas, y a nosotros mismos cuando queremos usar los datos, elaboramos este repositorio.

Los archivos `.R` con el sufijo *_script* producen los principales cuadros y gráficos de los compendios estadísticos, los cuáles se encuentran guardados en la ruta `Output/Cuadros` o `Output/Graficos`. La numeración de cuadros y gráficos corresponde a la de los documentos publicados por la misma DT. Los datos de los archivos `pdf` se pasaron a `R` mediante dos formas alternativas: (1) se copiaron y pegaron las tablas como texto en el script del programa, o (2) Con la aplicación online `I love pdf` se transformaron a `xlsx` los archivos `pdf`. Mediante los paquetes `readxl` y `openxlsx` estos archivos excel fueron leídos y posteriormente ordenados.

En el archivo *NUEVOS CUADROS Y GRAFICOS* se proponen formas alternativas de calcular las tasas de sindicalización y otros indicadores en base a datos actualizados (en desarrollo). Los resultados de esto se presentan en la ruta `Output/Nuevo`.

El resumen y descarga directa de los cuadros más relevantes se presenta aquí:

### 1. Organizaciones Sindicales (OOSS)

[Cuadro1](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Cuadros/1.%20OOSS/cuadro1.xlsx). Cantidad de sindicatos activos, poblacion afiliada a sindicatos activos, fuerza de trabajo y tasas de sindicalización.

[Cuadro2](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Cuadros/1.%20OOSS/cuadro2.xlsx). Cantidad de trabajadores afiliados a sindicatos activos, fuerza de trabajo ocupada, y tasa de sindicalización, según sexo.

[Cuadro3](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Cuadros/1.%20OOSS/cuadro3.xlsx). Cantidad de sindicatos activos a nivel nacional, por rama de actividad económica.

[Cuadro4](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Cuadros/1.%20OOSS/cuadro4.xlsx). Cantidad de afiliados a sindicatos activos a nivel nacional, por rama de actividad económica.

[Cuadro5](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Cuadros/1.%20OOSS/cuadro5.xlsx). Cantidad de afiliados a sindicatos activos a nivel nacional, por rama de actividad económica y sexo.

[Cuadro7](https://github.com/ObservatorioSindical/COMPENDIOS_DT/raw/main/Output/Nuevo/cuadro7.xlsx). Tamaño sindical promedio (cantidad de afiliados sobre la cantidad de sindicatos activos), por rama de actividad ecónomica.    

### 2. Negociaciones colectivas

### 3. Huelgas

[Cuadro1](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Cuadros/3.%20HUELGAS/cuadro1.xlsx). Cantidad de huelgas y trabajadores involucrados, por estado de huelga.

[Cuadro2](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Cuadros/3.%20HUELGAS/cuadro2.xlsx). Días huelgas.

[Cuadro3](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Cuadros/3.%20HUELGAS/cuadro3_huelgas.xlsx). Cantidad de huelgas por sector económico.

[Cuadro4](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Cuadros/3.%20HUELGAS/cuadro3_TC.xlsx). Trabajadores comprometidos en huelgas por sector económico.

### 4. Nuevos cuadros y gráficos

[Cuadro1](https://github.com/nicolasrattor/COMPENDIOS_DT/raw/main/Output/Nuevo/Tasas_actualizadas.xlsx). Tasas de sindicalización nacionales actualizadas (INE CENSO 2017).

[Cuadro2](). Tasas de sindicalización por rama de actividad ecónomica (INE CENSO 2017). En desarrollo. 

[Cuadro3](https://github.com/Andreas-Lafferte/ENE-Chile/raw/main/output/tasas_privados_INE.xlsx). Tasas de sindicalización asalariados privados por rama de actividad ecónomica (INE CENSO 2017). 

[Cuadro4](https://github.com/Andreas-Lafferte/ENE-Chile/raw/main/output/tasas_privados_sexo_rama_INE.xlsx). Tasas de sindicalización asalariados privados por sexo y rama de actividad ecónomica (INE CENSO 2017). 