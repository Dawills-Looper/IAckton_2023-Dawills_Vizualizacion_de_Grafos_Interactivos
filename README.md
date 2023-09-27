# IAckton2023

# Red de Relaciones 2023

Este proyecto se centra en visualizar y analizar las relaciones de licitaciones y premios (awards) en el año 2023 en el ámbito de obras artísticas, científicas o literarias. La visualización se realiza mediante un grafo interactivo que muestra las entidades compradoras y proveedoras, así como las conexiones entre ellas. Este README proporciona una descripción general de cómo funciona el proyecto y cómo utilizarlo.

## Contenido

- [Descripción General](#descripción-general)
- [Requisitos](#requisitos)
- [Instrucciones de Uso](#instrucciones-de-uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Dependencias](#dependencias)
- [Licencia](#licencia)

## Descripción General

El proyecto consta de las siguientes partes clave:

1. **Carga de Datos**: El código carga datos desde un archivo JSON que contiene información sobre licitaciones y premios en 2023 en el ámbito de obras artísticas, científicas o literarias.

2. **Procesamiento de Datos**: Los datos se procesan y se crean trazas para compradores y proveedores, mostrando sus relaciones. Se calcula el valor total de los enlaces para cada entidad compradora y se muestra esta información en los nodos del grafo.

3. **Visualización Interactiva**: Utilizando Plotly y Dash, se crea una visualización interactiva del grafo que muestra las relaciones entre compradores y proveedores. La leyenda se ha configurado para separar los nodos en "Compradores" y "Proveedores" para facilitar la comprensión.

4. **Guardado de Datos**: Se guarda el grafo en un archivo GEXF que puede ser utilizado en herramientas de visualización de redes como Gephi.

## Requisitos

Asegúrate de tener instaladas las siguientes dependencias antes de ejecutar el código:

- Python 3
- Pandas
- NetworkX
- Plotly
- Dash

Puedes instalar estas dependencias utilizando `pip`:

```bash
pip install pandas networkx plotly dash
```

## Instrucciones de Uso

1. Descarga el archivo JSON que contiene los datos de licitaciones y premios en 2023 en el ámbito de obras artísticas, científicas o literarias.

2. Ejecuta el código proporcionado en un entorno de Python.

3. Abre el navegador y accede a la dirección proporcionada (por lo general, `http://127.0.0.1:8050/`) para ver la visualización interactiva del grafo.

4. Explora la visualización para analizar las relaciones entre las entidades compradoras y proveedoras.

## Estructura del Proyecto

- `red_de_contrataciones.py`: El archivo principal que contiene el código para cargar, procesar y visualizar los datos.
- `red_de_contrataciones.gexf`: El archivo GEXF que contiene el grafo guardado.
- `README.md`: Este archivo que proporciona información sobre el proyecto.

## Dependencias

- [Python](https://www.python.org/): El lenguaje de programación utilizado para el proyecto.
- [Pandas](https://pandas.pydata.org/): Una biblioteca de análisis de datos que se utiliza para manipular los datos.
- [NetworkX](https://networkx.github.io/): Una biblioteca de Python para crear, manipular y estudiar la estructura, dinámica y funciones de redes complejas.
- [Plotly](https://plotly.com/): Una biblioteca de gráficos interactivos para Python.
- [Dash](https://dash.plotly.com/): Un framework de Python para crear aplicaciones web interactivas.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles.

---

Puedes personalizar este README según las necesidades de tu proyecto, incluyendo información adicional o enlaces relevantes. También puedes agregar ejemplos de capturas de pantalla de la visualización interactiva si lo deseas.interactiva si lo deseas.





