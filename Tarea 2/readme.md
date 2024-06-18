# Analizar Triángulos y Rectángulos en Grafos Utilizando PySpark junto con Neo4j y AuraDB

Este proyecto proporciona una guía paso a paso sobre cómo analizar triángulos y rectángulos en grafos provenientes de una base de datos de grafos utilizando Neo4j mediante AuraDB. AuraDB es una base de datos como servicio (DBaaS) de Neo4j que permite a los desarrolladores desplegar y gestionar bases de datos gráficas en la nube de manera fácil y rápida.


## Requisitos Previos

Antes de comenzar, asegúrate de tener los siguientes elementos:

- Una cuenta en [Neo4j Aura](https://aura.neo4j.com/)
- Acceso a una instancia de AuraDB
- Credenciales de acceso (URI, usuario y contraseña de la base de datos)
- [Neo4j Desktop](https://neo4j.com/download/) instalado (opcional, pero recomendado para pruebas locales)
- [Neo4j Browser](https://neo4j.com/developer/neo4j-browser/) o cualquier otra herramienta para ejecutar consultas Cypher

## Configuración del Entorno

1. **Obtener las Credenciales de AuraDB**: 
   - Inicia sesión en tu cuenta de AuraDB y selecciona la base de datos a la que deseas subir los datos.
   - Copia la URI de conexión, el nombre de usuario y la contraseña.

2. **Instalar la Biblioteca Neo4j para Python** (opcional, si se usa un script en Python en local):
   ```sh
   pip install neo4j

3. **Instalar la Biblioteca Neo4j para Python** (opcional, si se usa un script en Python en local):
    ```sh
    pip install pyspark

#  Ejecucion del Jupyter Notebook del proyecto.

- Navega a la carpeta `cora` que se encuentra en el mismo directorio que este `README.md`.
- Descarga la carpeta junto con los archivos y dejarlo en el mismo directorio al Jupyter Notebook `Tarea 2 BDM.ipynb`.
- Abre el Jupyter Notebook del proyecto en `Google Colab` o `Local`.
- Cambia las variables de `URI` `AUTH` correspondientes a sus datos obtenidos de la seccion de neo4j de manera local o en la nube.
- Ejecutar los Scripts en el Jupyter Notebook para subir los datos `load_papers` y `load_relationships`.
