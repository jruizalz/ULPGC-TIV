# 43759 - Tecnologías de la Imagen y Vídeo

Este repositorio contiene un conjunto de *notebooks* de [Jupyter](https://jupyter.org/) correspondientes a la asignatura de **43579 - Tecnologías de la Imagen y Vídeo** que se imparte en el Grado en Ingeniería en Tecnologías de la Telecomunicación de la [Universidad de Las Palmas de Gran Canaria (ULPGC)](https://www.ulpgc.es/). Se trata de un trabajo en curso pensado **exclusivamente** para la docencia en la asignatura y universidad mencionadas, si bien las personas interesadas pueden tomar ideas y proponer mejoras, siempre con propósito **exclusivamente** docente, siendo conscientes de que el software puede tener errores y que no debe utilizarse para ninguna aplicación fuera de la docencia universitaria. Debe darse crédito a este repositorio y a su coordinador responsable de la asignatura, Prof. Juan Ruiz Alzola y a su equipo del Grupo de Tecnología Médica y Audiovisual de la ULPGC.

## Ejecución de los *Notebooks*

La opción recomendada es que los estudiantes instalen un entorno básico con la distribución gratuita de [Anaconda](https://www.anaconda.com/) en sus ordenadores personales para ejecutarlo localmente. Dado que el repositorio está actualmente en desarrollo, deben visitar con frecuencia el repositorio para descargar los *notebooks* actualizados. Esto puede hacerse de forma muy sencilla si tienen sus propias cuentas personales en [GitHub](https://github.com/) y un conocimiento básico de [Git](https://git-scm.com/).

No obstante, lo estudiantes tienen la posibilidad de ejecutar los *notebooks* sin necesidad de instalar nada, directamente desde sus navegadores de Internet. 

### Google Colab

Si tienen cuenta en Google pueden pulsar en la etiqueta de [Google Colab](https://colab.research.google.com/), que aparece en la parte superior de varios *notebooks*. Con ello el *notebook* se abre en el entorno de ejecución, en la nube de Google, sin que haya que instalar ningún software localmente. No obstante, la gestión de los ficheros debe hacerse a mano con la interfaz gráfica de Colab, según se resumen en los *notebooks* bajo la etiqueta de *Open in Colab*. En principio no hay persistencia de los resultados, si bien puede utilizarse Google Drive para almacenar *notebooks* y configurar cierta persistencia. Si optan por utilizar Google Drive deben tener en cuenta que hay que concederle permisos de acceso a Google Colab y a los *notebooks* al Google Drive personal, por lo que debe hacerse con sumo cuidado para no dejar accesibles los datos almacenados en el mismo a terceros.

### MyBinder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ULPGC-GTMA/ULPGC-TIV/HEAD)

Se trata de un servicio gratuito para ejecutar en la nube repositarios de *notebooks*, aunque puede resultar algo lento. Para ejecutarlo hay que pulsarse la etiqueta que está al comienzo de este documento y se podrán abrir los *notebooks* en el entorno MyBinder. Adviértase que las sesiones de MyBinder son temporales, de forma que los cambios que se hagan sobre los *notebooks* se pierden entre sesiones, aun cuando se almacenen, una vez se cierra la ventana del navegador. Sí es posible descargar los *notebooks* al ordenador local.

Puede accederse a la ejecución en MyBinder también en <https://mybinder.org/v2/gh/ULPGC-GTMA/ULPGC-TIV/HEAD>

### Anaconda Cloud

Si se desea tener persistencia, la mejor opción es [Anaconda CLoud](https://anaconda.cloud/), que ofrece de forma gratuita una máquina virtual con 5 GB de almacenamiento. Es necesario clonar en la máquina virtual el repositorio. Puede ser necesario instalar un entorno virtual con los paquetes de Python que se necesiten, si bien muchos *notebooks* correrán con alguno de los entoornos preinstalados. Es necesario abrir una cuenta.
