## News Retrieval and Embedding System (RPP RSS Feed)

Este módulo implementa un flujo reproducible para ingerir noticias de RPP Perú (https://rpp.pe/rss), tokenizarlas, generar embeddings con SentenceTransformers, almacenarlas en ChromaDB y consultarlas mediante un retriever orquestado con LangChain.

El objetivo principal es comprender cómo funcionan los modelos de lenguaje (LLMs), desde el proceso de tokenización y representación semántica (embeddings) hasta la búsqueda y recuperación de información en un entorno vectorial. Este laboratorio permite observar de forma práctica cómo los modelos convierten texto en representaciones numéricas que facilitan la similitud contextual y la organización inteligente de documentos.

Los resultados generados noticias procesadas, embeddings y consultas se almacenan en el directorio /data/, permitiendo su posterior análisis, validación o reutilización en otros módulos del proyecto, al tulimo se podria imnterpetar como un analissi de sentimieto.

Finalmente, este sistema sienta las bases para tareas más avanzadas, como la clasificación automática de noticias o el análisis de sentimiento, demostrando cómo los LLMs pueden utilizar la información vectorizada para interpretar y categorizar el contenido textual de manera contextual y precisa.