## DESCRIPCIÓN

Bienvenido a este repositorio, el cual contiene todo el material desarrollado para el proyecto final de la materia de Aprendizaje No Supervisado, la cual hace parte de la Maestría en Analítica de la Universidad de los Andes. Nuestro trabajo se centra en la aplicación de Minería de Datos, utilizando avanzadas técnicas de aprendizaje no supervisado para lograr una reducción de la dimensionalidad y segmentación de datos, con el objetivo de descubrir patrones reveladores.

Este proyecto es especialmente relevante para comprender cómo las variables demográficas y geográficas de estudiantes, colegios y familias influyen en los puntajes obtenidos en las Pruebas Saber 2020 (tanto para los calendarios A como B). A través de este análisis, buscamos entender las dimensiones que podrian afectar el rendimiento academico y resultados obtenidos en las pruebas, proporcionando así valiosos "insights" que podrían guiar futuras decisiones educativas y políticas públicas en Colombia.

Este repositorio incluye todos los archivos y reportes generados durante el desarrollo del proyecto. Cada componente está descrito en detalle, y se actualizará continuamente conforme se avanza en nuevas iteraciones del análisis. 


## Estructura
Root del proyecto 
  - Primera Entrega : Esta carpeta contiene los archivos que han sido desarrollados para la primera fase/entrega del proyecto
    - Codigo: En esta carpeta se ubican los archivos con el codigo en python que se ha desarrollado para llevar a cabo nuestro analisis.
        - PruebasSaber-DataMining.ipynb: Este archivo contiene el codigo desarrollado para la primera entrega, en el cual se realiza la carga inicial de los     datos, analisis descriptivo y se generar los reportes que permiten analizar cada una de las variables que ofrece la base de datos de estudiantes.
    - data: En esta carpeta se encuentra los datos en formato .csv, en el encontraran dos arhivos, uno con los datos de los estudiantes que presentarón las pruebas en el calendario A del 2020 y otro en el calendario B del 2020
      - Saber_11__2020-1_20240828.csv: Datos de estudiantes Calendrio B
      - Saber_11__2020-2_20240828.csv: Datos de estudiantes Calendario A
    - Reportes: En esta carpeta se alojan los reportes que han sido generados a partir de los datos, se encuentra un reporte con el estado de los datos frente a nulos y otro generado a partir de pandas_profiler, el cual describe a detalle cada variable asociada a los datos.
      - estadisticasDescriptivasSaber2020.html: Contiene las estadisticas descriptivas de cada una de las variables del dataframe y un analisis detallado de la información de cada variable.
      - variable_report.csv: reporte del estado de cada variable con respecto a la cantidad de datos faltantes
      - Primera_Entrega_Proyecto_Aprendizaje_No_Supervisado.pdf: Documento preliminar de avance del proyecto, contiene la información del resumen del trabajo, objetivos, metodologia a desarrollar como antecedentes que son referentes de otras iniciativas similares que se han realizado relevantes para nuestro proyecto. 


