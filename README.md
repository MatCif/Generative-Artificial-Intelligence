# README: Laboratorio de Inteligencia Artificial Generativa para los Negocios

## Descripción General
Este archivo es un cuaderno Jupyter diseñado para introducir y explorar el uso de tecnologías de inteligencia artificial generativa aplicadas al ámbito de los negocios. El enfoque principal radica en configurar un entorno adecuado para trabajar con modelos de lenguaje avanzados y herramientas asociadas. Este laboratorio se desarrolla en el marco del curso **Inteligencia Artificial Generativa** del **Magíster en Analítica de Negocios**.

## Contenido
El cuaderno contiene un total de 22 celdas, distribuidas de la siguiente manera:

- **Celdas de Código:** 6
  Estas celdas incluyen comandos clave para la instalación y configuración de las librerías necesarias.
  - Ejemplo de comandos:
    ```python
    # Instalación de librerías necesarias
    !pip install --upgrade pip
    !pip install torch psutil transformers sentence-transformers langchain langchain-huggingface chromadb
    !pip install langchain-community
    !pip install pypdf
    !pip install --upgrade transformers langchain pypdf psutil chromadb sentence-transformers
    ```

- **Celdas Markdown:** 16
  Estas celdas probablemente contienen explicaciones, contextos teóricos, y pasos detallados para el uso práctico de las herramientas.

## Tecnologías y Herramientas Utilizadas
El cuaderno hace uso de las siguientes librerías y frameworks:

1. **Torch:** Para cálculos tensoriales y modelos de aprendizaje profundo.
2. **Transformers:** Librería de modelos de lenguaje preentrenados como GPT, BERT, etc.
3. **Sentence-Transformers:** Para realizar tareas de similaridad semántica y embeddings.
4. **LangChain:** Un marco diseñado para construir aplicaciones basadas en modelos de lenguaje.
5. **ChromaDB:** Herramienta de almacenamiento y recuperación de datos semánticos.
6. **PyPDF:** Procesamiento de documentos PDF.
7. **Psutil:** Para obtener información sobre el uso del sistema y administración de procesos.

## Objetivos del Laboratorio
1. Configurar un entorno funcional para la experimentación con modelos de lenguaje generativos.
2. Demostrar la integración de herramientas avanzadas en flujos de trabajo empresariales.
3. Proveer una base para desarrollar soluciones innovadoras en inteligencia artificial generativa aplicadas a los negocios.

## Instrucciones de Uso
1. **Preparación del Entorno:**
   - Asegúrese de tener instalado Python 3.7 o superior.
   - Ejecute las celdas de instalación para configurar las dependencias.

2. **Exploración:**
   - Lea las celdas Markdown para obtener contexto y explicaciones detalladas.
   - Ejecute las celdas de código en el orden sugerido.

3. **Requisitos Adicionales:**
   - Conexión a Internet para descargar las librerías y modelos necesarios.
   - Espacio suficiente en disco para almacenar modelos preentrenados y otros archivos temporales.

## Recomendaciones
- Utilice entornos virtuales (por ejemplo, `venv` o `conda`) para evitar conflictos de dependencias.
- Verifique que todas las librerías estén actualizadas antes de iniciar.
- Si trabaja en un entorno en la nube (Google Colab, AWS, etc.), ajuste las configuraciones según los recursos disponibles.

## Notas Adicionales
Este cuaderno es una herramienta educativa y experimental. Para implementaciones en producción, se recomienda revisar la documentación oficial de las librerías utilizadas y aplicar las mejores prácticas en seguridad y escalabilidad.


