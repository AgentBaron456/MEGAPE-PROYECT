# Integrantes
- *Vanessa Lucía Bernal Ruiz.*

- *Kevin Andrés Bedoya David.*

- *Iván Edwin Cando.*

- *Juan Andrés Barón Vásquez.*

Equipo de trabajo del Proyecto Integrador de Algoritmia y Programación 2026-2.

## Vínculos académicos y descripción

* #### Vanessa Lucía Bernal Ruiz
Estudiante de Ingeniería Industrial de la Universidad de Antioquia.

**Habilidades y fortalezas:** Organización, responsabilidad, trabajo en equipo y capacidad para analizar y solucionar problemas.

* #### Kevin Andrés Bedoya David
Estudiante de Ingeniería Industrial de la Universidad de Antioquia.

**Habilidades y fortalezas:** Adaptabilidad, proactivo, comunicación asertiva e interpretación de informacion para la toma de decisiones.

* #### Iván Edwin Cando
Estudiante de Ingeniería Industrial de la Universidad de Antioquia.

**Habilidades y fortalezas:** Adaptabilidad, responsabilidad, trabajo en equipo, capacidad de aprendizaje y pensamiento analítico.

* #### Juan Andrés Barón Vásquez
Estudiante de Ingeniería Industrial de la Universidad de Antioquia.

**Habilidades fortalezas:** Adaptabilidad, inteligencia emocional, inteligencia social, gestión del tiempo, pensamiento crítico y resiliencia.


## Nombre del proyecto y detalles

### PQRTrack – Sistema de Gestión de PQRS

<img width="1080" height="1080" alt="Post de Instagram Servicio Atención al cliente Ilustrado Sencillo Verde (1)" src="https://github.com/user-attachments/assets/2c49744f-6c02-46ce-8c7c-c6a186f17c53" />

El proyecto consiste en el desarrollo de un programa de software para la gestión de Peticiones, Quejas, Reclamos y Sugerencias (PQRS), cuyo fin permitirá registrar las solicitudes recibidas por distintos canales, asignarles un número de radicado, hacer seguimiento a su estado y calcular los tiempos de respuesta, facilitando así el control y fin de cada caso. Con esto se busca reemplazar el manejo tradicional de la información mediante papel y lápiz por un programa organizado y optimizado.

## Licencia del software

Este proyecto se distribuye bajo la **Licencia MIT**. Ver el archivo [`LICENSE`](LICENSE) para el texto completo.

## Reporte de visión
 - ### Descripción del software: 
 El software es una aplicación desarrollada en Python que permite registrar, almacenar, consultar y gestionar las peticiones, quejas, reclamos y sugerencias (PQRS) recibidas por PQRTrack. El sistema busca organizar la información de manera estructurada, facilitar el seguimiento de cada solicitud y generar reportes que permitan analizar la atención apropiada de los casos.
 
 - ### Objetivos del software: 
 El objetivo al usar Python es poder optimizar todos los procesos dentro de las actividades del gestor de PQRS, especialmente para mejorar sustancialmente su gestión de las peticiones, quejas, reclamos y sugerencias que le llegan día a día desde distintas fuentes, haciéndolo mucho más eficiente y organizado.

- ### Beneficios al utilizar Python:
 Unos de los beneficios al usar Python para la creación del programa es su accesibilidad y multiplataformidad, al igual que tanto su facilidad de uso y aprendizaje como su facilidad a la hora de darse a explicar y atender.

## Especificación de requisitos

### Requisitos funcionales
- El sistema debe permitir registrar una nueva PQRS, solicitando todos los datos necesarios para su radicación.
- El sistema debe validar los datos ingresados por el usuario, incluyendo nombres, números telefónicos, direcciones de correo electrónico y fechas.
- El sistema debe asignar a cada PQRS un número de radicado consecutivo y almacenar la información en cuatro archivos planos independientes, según el tipo de solicitud.
- El sistema debe permitir consultar las PQRS registradas y su estado actual.
- El sistema debe permitir gestionar y actualizar la información almacenada.
- El sistema debe generar reportes estadísticos a partir de la información registrada, incluyendo el promedio de días de respuesta de las solicitudes y cinco estadísticas adicionales, aún por definir según las necesidades de gestión del proyecto.
- El sistema debe permitir la lectura y escritura de los archivos utilizados para almacenar la información.

### Requisitos no funcionales
- **Usabilidad:** el sistema debe contar con un menú de consola claro y comprensible, que permita a un administrador sin conocimientos técnicos utilizarlo sin dificultad.
- **Confiabilidad:** el sistema debe almacenar correctamente la información registrada, sin pérdida ni alteración de los datos entre operaciones.
- **Seguridad:** la información registrada debe manejarse de forma adecuada, evitando modificaciones no autorizadas sobre los archivos planos.
- **Rendimiento:** el sistema debe procesar las consultas y los registros en un tiempo razonable, dado el volumen de datos esperado para un proyecto académico.
- **Mantenibilidad:** el código debe estar organizado en los módulos `validaciones.py`, `archivos.py` y `reportes.py`, cada uno con una responsabilidad clara, para facilitar su modificación y mantenimiento.
- **Compatibilidad:** el software debe poder ejecutarse en cualquier entorno que cuente con Python 3, sin depender de librerías externas adicionales.
- **Integridad:** el sistema debe validar los datos antes de almacenarlos, evitando que se guarde información incompleta, mal formateada o inconsistente.

## Plan de proyecto

### Actividades
- 1 **Análisis y planificación:** Revisar los requisitos del sistema, definir el alcance y organizar las tareas del equipo.
- 2 **Diseño de la estructura del programa:** Definir las clases, objetos, archivos y módulos que tendrá el proyecto.
- 3 **Creación de archivos y manejo de datos:** Preparar los cuatro archivos planos independientes para peticiones, quejas, reclamos y sugerencias.
- 4 **Desarrollo de validaciones:** Implementar las validaciones para nombres, documentos, teléfonos, correos, fechas, direcciones y demás datos solicitados.
- 5 **Desarrollo del registro PQRS:** Crear el proceso para registrar una nueva PQRS, asignar el id consecutivo y almacenar la información correspondiente.
- 6 **Consulta y actualización:** Desarrollar las funciones para consultar las PQRS registradas, visualizar su estado y actualizar la informacion permitida.
- 7 **Generación del radicado:** Crear el comprobante en formato TXT con el formato ASCII de 120 caracteres y la informacion requerida.
- 8 **Desarrollo de estadísticas:** Implementar el promedio de días de respuesta y las cinco estadísticas adicionales selecionadas por el equipo.
- 9 **Pruebas e integración:** Realizar pruebas de funcionamiento, detectar errores, verificar las validaciones e integrar todos los modulos.
- 10 **Documentación y organización final:** Elaborar la documentación, organizar las carpetas del proyecto t preparar el repositorio de GitHub.  

### Cronograma

### Presupuesto
Para 2026, el SMLMV establecido es de $1.750.905.
Para estimar el valor de cada hora de trabajo académico usamos la equivalencia de 240 horas mensuales:

**Valor hora:** $1.750.905 / 240 = $7.295,44

**Valor total del proyecto:** 50 horas x $7.295,44 = $364.772 aproximadamente 

 
