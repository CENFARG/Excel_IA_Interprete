# Chatbot para Análisis de Datos con IA y Excel

Esta herramienta permite analizar y visualizar datos de archivos Excel a través de una interfaz de chatbot intuitiva basada en Gradio. Utilizando la API de OpenAI, LangChain, Pandas y Matplotlib, el proyecto facilita consultas en lenguaje natural, generación de perfiles de datos avanzados, comparaciones entre columnas, filtrados y búsquedas, generando además reportes en Excel.

---

## ¿Qué hace esta herramienta?

- **Consulta Interactiva:** Permite formular preguntas sobre el contenido de un archivo Excel en lenguaje natural.  
- **Perfil de Datos Completo:** Genera análisis detallados del DataFrame, incluyendo estadísticas descriptivas, calidad de datos y recomendaciones basadas en condiciones del usuario.  
- **Comparación de Columnas:** Compara dos columnas (numéricas o categóricas) y presenta visualizaciones y estadísticas relevantes.  
- **Búsqueda Avanzada y Filtrado Natural:** Traduce consultas complejas a código Python para filtrar y extraer información de forma dinámica.  
- **Generación de Reportes:** Exporta los resultados y análisis en archivos Excel, incluyendo tablas dinámicas, muestras y resúmenes estadísticos.

---

## Tecnologías y Dependencias

Esta herramienta utiliza:

- **Gradio:** Interfaz gráfica para interactuar con el chatbot.  
- **Pandas:** Manipulación y análisis de datos.  
- **Matplotlib:** Visualización de datos.  
- **Openpyxl:** Lectura y escritura de archivos Excel.  
- **LangChain (community, openai, experimental):** Integración con la API de OpenAI y creación de agentes conversacionales.  
- **OpenAI API:** Motor de lenguaje natural para interpretar y responder consultas.

Las dependencias se instalan automáticamente al cargar el notebook, por lo que no es necesario configurarlas manualmente.

---

## Abrir en Google Colab

¡Prueba esta herramienta de forma inmediata en Google Colab! Haz clic en el botón para abrir y ejecutar el notebook:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OarofWoBTkdwgubFZuVEY8V_Se0urJF0?usp=copy)

---

## ¿Cómo usarlo?

1. **Clona o descarga el repositorio** y abre el notebook principal (`excelIAPandas_OPENAI_v02.ipynb`) en Google Colab o en tu entorno local.
2. **Introduce tu API Key de OpenAI** y sube el archivo Excel que deseas analizar.
3. **Interactúa mediante el chatbot:**  
   - Envía consultas en lenguaje natural (por ejemplo, “Mostrar las primeras 10 filas” o “Generar perfil de datos”).  
   - Escoge entre herramientas adicionales como comparación de columnas o búsqueda avanzada.
4. **Revisa los resultados:**  
   - Las respuestas se muestran en la interfaz del chatbot.  
   - Se generan archivos Excel con resultados, perfiles y visualizaciones, que podrás descargar.

---

## Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Puedes usar, modificar y distribuir el código libremente, de acuerdo con los términos de la licencia.

---

## Contacto

- **Desarrollador:** Gonzalo F. Recalde  
- **Coautor:** Pablo A. Bonnecaze  
- **Empresa:** [CENF](https://www.cenfarg.com)  
- **Email:** [capacitaciones.cenf@gmail.com](mailto:capacitaciones.cenf@gmail.com)

¡Gracias por usar esta herramienta y felices análisis de datos con IA!
