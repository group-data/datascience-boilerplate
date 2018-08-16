# Data Science Boilerplate

## Requisitos

* Docker CE
* Docker-Compose

* En MacOS docker-compose esta incluido en Docker CE.

## Contenido

* Template que utiliza la imagen de Docker de https://hub.docker.com/r/jupyter/datascience-notebook/ la cual usa como base Python 3 con las librerias Pandas, Scipy, Numpy y los lenguajes Julia y R.

## Ejecución

1. Situado en la raíz del proyecto. Ejecutar:

```bash
$ docker-compose up
```
2. Acceder la dirección que muestra la salida de la terminal:
  2.1 En MacOS se debe ingresar la dirección como 127.0.0.1.
     * Ejemplo:  http://127.0.0.1:8888/token=d12db114978a0dfcb15cc2180aa8891afb985866e7127cee

## Material de ayuda

* https://www.analyticsvidhya.com/blog/2018/05/starters-guide-jupyter-notebook/
* http://pythonforengineers.com/introduction-to-pandas/
* https://docs.scipy.org/doc/numpy/user/quickstart.html
