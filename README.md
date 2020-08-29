# Propedeutico

Este es el repositorio para el propedéutico (aka prope) de la MCD en el ITAM impartido por el **Prof. Erick Palacios Moreno**, github: [palmoreck](https://github.com/palmoreck).

### Dar click en [liga](https://drive.google.com/file/d/1A5FF9lOFYXb4CdbAQaOp79x1A-9-j36b/view?usp=sharing) para el temario.

### Dar click en [liga2](https://hackmd.io/@palmoreck/rJQQIEmbv) para una presentación de introducción al prope verano 2020.

### Dar click en el siguiente botón para unirse\* al chat del verano del 2020 en [gitter](https://gitter.im/): [![Gitter](https://badges.gitter.im/prope-2020/community.svg)](https://gitter.im/prope-2020/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) 

\***Se puede hacer el registro con su cuenta de [github](https://github.com/)**.

### En el prope utilizaremos la imagen de [docker](https://www.docker.com/) `palmoreck/jupyterlab_prope_r_kernel_tidyverse:2.1.4` cuya documentación la encuentran [aquí](https://github.com/palmoreck/dockerfiles/tree/master/jupyterlab/prope_r_kernel_tidyverse)\*. 

\* Tal imagen de docker se descarga con un `docker pull palmoreck/jupyterlab_prope_r_kernel_tidyverse:2.1.4` desde la terminal una vez hayan instalado docker en sus computadoras. Ver [herramientas/docker/](herramientas/docker/) para referencias de docker.

## Ramas del repositorio.

En este repositorio se han creado diferentes ramas que pueden ser accesadas como se aprecia en esta imagen:

<img width="320" alt="imagen" src="https://user-images.githubusercontent.com/3290689/83956287-05548100-a822-11ea-8398-12dc2bb8810f.png">

Seleccionar por ejemplo la rama **prope-2019-1** (u otra) para información del curso propedéutico de 2019.


**Dar click en [prope-2020](https://github.com/ITAM-DS/Propedeutico/tree/prope-2020) para la rama del curso del verano 2020.**

## Breve explicación del repositorio en la rama master.

En la carpeta [Python](/Python) encuentran temas del cálculo numérico en Python3\*.

En la carpeta [R](/R) encuentran temas de probabilidad y estadística en R\*.

En la carpeta [herramientas](/herramientas) encuentran información de herramientas como [docker](https://www.docker.com/), [git](https://git-scm.com/) y [bash](https://www.gnu.org/software/bash/).

\* Las notas de cada tema están escritas en [Jupyter notebooks](https://jupyter.org/). Ver [I python, You R, We Julia](https://blog.jupyter.org/i-python-you-r-we-julia-baf064ca1fb6) para algunas características de tales notebooks. Ver [notebook](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html) para funcionalidad de los notebooks. Ver [Jupyter kernels](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels) para una tabla de los [kernels](https://jupyter.readthedocs.io/en/latest/install-kernel.html) disponibles en jupyter (que hacen posible ejecutar instrucciones en el lenguaje R, por ejemplo, en tales notebooks).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/palmoreck/dockerfiles-for-binder/jupyterlab_prope_r_kernel_tidyerse?urlpath=lab/tree/Propedeutico) <--- al dar click en este botón, de una forma interactiva se pueden ejecutar los notebooks de jupyter tanto para Python como para R dentro de los directorios de [Python](/Python) y de [R](/R).

[![Run on Repl.it](https://repl.it/badge/github/palmoreck/dummy)](https://repl.it/@palmoreck/dummy) <--- este botón lo podrán encontrar en los directorios de [Python](/Python) y de [R](/R). Tal botón utiliza [repl.it](https://repl.it/) que ayuda a escribir códigos de forma colaborativa en el lenguaje de Python3, R y otros. Al dar click se crearán nuevos ***repl*** debajo de sus users de ***repl.it***.


## Organización de github classroom

La organización [prope-2020-gh-classroom](https://github.com/prope-2020-gh-classroom) fue creada para alojar repositorios de [github classroom](https://classroom.github.com/) (ver [github education](https://github.com/education)). Esta organización será nuestro *playground* para el curso de verano 2020 :)

Esta organización tiene integrados los siguientes botones de [repl.it](https://repl.it/) para el curso de verano 2020:

[![Run on Repl.it](https://repl.it/badge/github/prope-2020-gh-classroom/repo-for-repl.it-Python)](https://repl.it/@palmoreck/repo-for-replit-Python) (botón de **Repl.it para Python3 con prácticas *multiplayer* para el verano 2020**)

[![Run on Repl.it](https://repl.it/badge/github/prope-2020-gh-classroom/repo-for-repl.it-R)](https://repl.it/@palmoreck/repo-for-replit-R) (botón de **Repl.it para R con prácticas *multiplayer* para el verano 2020**)




## Índice de notas

Cada número contiene información del tema respectivo, dar click en el tema de interés.

**[Python](/Python)**

**Introducción:**

[0. Contenedor de docker para Python3](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/1_introduccion/0_contenedor_de_docker_para_Python3.ipynb)

[1. Información general](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/1_introduccion/1_informacion_general.ipynb)

[2. Core Python](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/1_introduccion/2_core_python.ipynb)

[3. Funciones y módulos](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/1_introduccion/3_funciones_y_modulos.ipynb)

[4. Módulos: numpy y matplotlib](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/1_introduccion/4_modulos_numpy_matplotlib.ipynb)

**Cálculo Diferencial e Integral:**

[1. Aproximación a derivadas e integrales de forma numérica](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/2_calculo_DeI/1_aproximacion_a_derivadas_e_integrales.ipynb)

[Ejemplo al no usar bloque de if name main en modulo](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/2_calculo_DeI/Ejemplo_al_no_usar_bloque_if_name_main_en_modulo.ipynb)

**Álgebra lineal:**

[0. Definiciones generales](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/3_algebra_lineal/0_definiciones_generales.ipynb)

[1. Ecuaciones lineales](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/3_algebra_lineal/1_ecuaciones_lineales.ipynb)

[2. Interpolación](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/3_algebra_lineal/2_interpolacion.ipynb)

[3. Mínimos cuadrados lineales](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/3_algebra_lineal/3_minimos_cuadrados.ipynb)

[4. SVD](https://github.com/ITAM-DS/Propedeutico/blob/master/Python/clases/3_algebra_lineal/4_SVD_y_reconstruccion_de_imagenes.ipynb)

**[R](/R)**

**Introducción:**

[0. Contenedor de docker para R](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/1_introduccion/0_contenedor_de_docker_para_R.ipynb)

[1. Información general](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/1_introduccion/1_informacion_general.ipynb)

[2. Core R](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/1_introduccion/2_core_R.ipynb)

[3. ggplot2](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/1_introduccion/3_ggplot2.ipynb)

**Probabilidad:**

[1. Elementos de probabilidad](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/2_probabilidad/1_elementos_de_probabilidad.ipynb)

[2. Propiedades de la probabilidad](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/2_probabilidad/2_propiedades_de_la_probabilidad.ipynb)

[3. Métodos de conteo](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/2_probabilidad/3_metodos_de_conteo.ipynb)

[4. Probabilidad condicional](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/2_probabilidad/4_probabilidad_condicional.ipynb)

[5. Independencia](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/2_probabilidad/5_independencia.ipynb)

[6. Teorema de Bayes](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/2_probabilidad/6_teorema_de_Bayes.ipynb)

[7. Variables aleatorias](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/2_probabilidad/7_variables_aleatorias.ipynb)

**Estadística:**

[1. Elementos de Estadística descriptiva](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/3_estadistica/1_elementos_de_estadistica_descriptiva.ipynb)

[2. Distribuciones comunes](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/3_estadistica/2_distribuciones_comunes.ipynb)

[3. Elementos de inferencia](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/3_estadistica/3_elementos_de_inferencia.ipynb)

[4. Regresión lineal](https://github.com/ITAM-DS/Propedeutico/blob/master/R/clases/3_estadistica/4_regresion_lineal.ipynb)
