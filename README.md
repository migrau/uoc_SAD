# Software para el analisis de datos. UOC - UB.

Repositorio creado para almacenar los archivos, gráficos y material necesario/utilizado para la realización del trabajo en grupo de la asignatura Software para el analisis de datos de la UOC - UB.

## Descripción del trabajo.

1. Buscad un conjunto de datos relacionado con la Bioestadística. Puede ser generado por
simulación, pueden ser datos incorporados en un paquete de R (no se usarán los paquetes
IRIS, IRIS3) u otros repositorios. Tenéis que explicar la procedencia de estos datos.
2. Explicad las variables de vuestro fichero, tipo, clasificación, etc... ¡Todo aquello que creáis
que es relevante!
3. Pensad un mínimo de cuatro de preguntas objetivo que queráis contestar con estos datos.
4. Haced el análisis descriptivo de los datos. Todo aquello que creáis que es necesario.
¡Resumid los datos a vuestro criterio pero con sentido! Pensad siempre en las preguntas
objetivo que queréis contestar. Si debéis recodificar variables.
5. Generad los gráficos que creáis necesarios para resumir de forma gráfica la información que
tenéis.

## Contenido del repositorio

* _Rscripts_. Contiene todos los scripts utilizados para resolver el ejercicio.
* _DatosEntrada_. Bases de datos utilizadas.

Información adicional sobre los puntos 2-4 podemos ir escribiendola en el wiki.

El informe final Rmarkdown donde escribir la memoria y generar los *plots* es *Rscripts/SAD_trabajoGrupo.Rmd*

## Cómo actualizar el repositorio.

(desde un terminal de linux/mac)

>1 -  Clonamos el repositorio:

    $ git clone https://github.com/migrau/uoc_SAD.git


>2 - Comprobamos que nuestro repositorio local está enlazado correctamente:

    $ cd uoc_SAD
    $ git remote -v 
    origin  https://github.com/migrau/uoc_SAD.git (fetch)
    origin  https://github.com/migrau/uoc_SAD.git (push)


>3 - Realizamos nuestros cambios. Una vez está preparado para subir:

    #Añade todos los ficheros "untracked"
    $ git add -A
    $ git commit -a

>4 - Actualizamos repositorio web.

    $ git push origin master


##### Documentación interesante sobre el uso de repositorios

[1, ](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos#Inspeccionando-un-repositorio-remoto)
[2, ](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)
[3, ](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-init)
[4.](http://classic.scottr.org/presentations/git-in-5-minutes/)
