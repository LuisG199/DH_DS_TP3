# Trabajo_Practico3
Trabajo Práctico

Prediccion de la distribucion de Pts en Partidos de la NBA.

En este apartado realizaremos el proceso de selección del conjunto de datos que vamos a modelar. En la primera sección nos concentraremos en operaciones sobre las filas del dataframe, a fin de seleccionar las observaciones que vamos a considerar y realizaremos limpieza de datos, mientras que en la segunda, trabajaremos sobre las columnas, con el objetivo de seleccionar las variables que vamos a utilizar en el proceso de aplicacion de distintos modelos de clasificacion.

En esta sección procedemos con la carga del DataSets por registros de lanzamientos en distintos partidos de NBA de la temporada 2014-2015 para el mismo disponemos de distintos feautures que caracterizan las habilidades del tirador y defensor para predecir si el primero acertara o fallara su tiro (Variable a predecir).

Por otro lado tambien contaremos con los stats de aquellos jugadores que realizan el lanzamiento asi como tambien los del defensor mas proximo que intentara bloquear el tiro.

## Configuración del Entorno

### Crear un nuevo entorno virtual

Primero, asegúrate de tener Python 3.x instalado en tu sistema. Luego, crea un nuevo entorno virtual:

```bash
python -m venv <environment_name>
```

### Activar el entorno virtual (Linux/Mac)

```bash
source <environment_name>/bin/activate
```

### Activar el entorno virtual (Windows)

```bash
<environment_name>\Scripts\activate
```

## Instalar Dependencias

Una vez que tengas el entorno virtual activado, puedes instalar las dependencias del proyecto desde el archivo `requirements.txt` usando pip:

```bash
pip install -r requirements.txt
```
