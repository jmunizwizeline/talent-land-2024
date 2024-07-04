# talent-land-2024
Tutorial básico de un caso de uso de GraphRAG usando langchain y Neo4j.

## Prerequisitos técnicos

-  **Python 3.10**: Disponer de Python instalado en el equipo con una versión mínima de 3.10.
-  **OpenAI API Key**: Disponer de una API Key de OpenAI.
-  **NEO4J**: Disponer de una instancia de la base de datos orientada a grafos Neo4j.

## Configuración proyecto

**Paso 1** - Descargar las dependencias del proyecto

En el fichero **requirements.txt** están definidas las dependencias necesarias de Python para poder correr la demo. Para importarlas debemos ejecutar el siguiente comando: 
```
pip install -r requirements.txt
```

**Paso 2** - Crear fichero .env e introducir los parámetros de configuración necesarios

Para poder funcionar hay que crear un fichero _.env_ en el raiz del proyecto que tenga las siguientes propiedades:

-  **OPENAI_API_KEY**: API Key para poder conectarnos al LLM que usaremos en la demo, OpenAI.
-  **NEO4J_CONNECTION_URL**: URL de conexión a Neo4j, la base de datos orientada a grafos que usaremos en la demo.
-  **NEO4J_USER**: Usuario para conectarnos a la bbdd.
-  **NEO4J_PASSWORD**: Password para conectarnos a la bbdd.
