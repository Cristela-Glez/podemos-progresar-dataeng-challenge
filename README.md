# Podemos Progresar -Test Data Engineering 

Autor: Cristela Glez Morales
Ingeniera de Datos con mas de 10 años de experiencia, especializada en ambientes cloud y bigdata. Especialista
en diseño de pipelines de datos, procesos ETL/ELT, automatización y optimización de flujos de datos.

Enfoque arquitectónico: 
Se busca una solución escalable en Amazon Redshift, para un modelo de Microcréditos grupales basados en lo siguientes puntos:
Un modelado de Datos por ejemplo un Diseño dimensional con tablas de Hechos y Dimensiones, que sea escalable podríamos utilizar distkey o sortkey para consultas mas optimizadas. Parte importante es tener en cuenta la Gobernanza de Datos, así como el control de accesos y roles, linaje de datos para la trazabilidad, por ejemplo un catalogo de metadatos. Particionamiento por región, Pipelines(Sincronización offline-first, batch)

## Estructura del repositorio
redshift/: Arquitectura y optimizaciones para Amazon Redshift(DWH).
pyspark/: Scripts de procesamiento de datos.
devops/: Automatización de pipelines CI/CD.
arquitectura-eventos/: Diseño de sistema basado en eventos.
