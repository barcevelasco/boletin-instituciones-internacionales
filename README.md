# Boletín Mensual de Instituciones Internacionales

Este proyecto extrae, procesa y organiza publicaciones recientes de instituciones internacionales relevantes para la banca central y el análisis económico. Genera un boletín mensual en formato Word y ofrece una interfaz web interactiva para consultar y filtrar los documentos.

## Instituciones cubiertas

- Fondo Monetario Internacional (FMI)
- Banco Interamericano de Desarrollo (BID)
- Banco Mundial (BM)
- Organización para la Cooperación y el Desarrollo Económicos (OCDE)
- Banco de Pagos Internacionales (BPI)
- Foro Económico Mundial (FEM)
- Consejo de Estabilidad Financiera (CEF)
- Banco de Inglaterra (BoE)

## Características

- Extracción automatizada de publicaciones, reportes, discursos y blogs.
- Procesamiento de fechas, títulos, autores y enlaces.
- Clasificación por organismo y categoría (Publicaciones Institucionales, Investigación, Discursos).
- Generación de boletín mensual en Word.
- Interfaz web con Streamlit para consulta y filtrado.
- Exportación a Excel y Word.

## Tecnologías utilizadas

- Python 3
- Streamlit
- Pandas
- Requests / Cloudscraper / Selenium
- BeautifulSoup
- python-docx
- dateutil

## Estructura del proyecto

```text
.
├── app.py                # Aplicación principal (Streamlit)
├── requirements.txt      # Dependencias
├── .gitignore            # Archivos ignorados por Git
└── README.md             # Este archivo
Instalación y uso
Clona el repositorio:

bash
git clone https://github.com/barcevelasco/Bolet-n-Mensual-Actualizado.git
cd Bolet-n-Mensual-Actualizado
Instala las dependencias:

bash
pip install -r requirements.txt
Ejecuta la aplicación:

bash
streamlit run app.py
Abre tu navegador en http://localhost:8501.

Notas
Este proyecto es de carácter personal y no tiene ninguna relación oficial con Banxico ni con ninguna otra institución.

Los datos extraídos provienen de fuentes públicas disponibles en internet.

El código se distribuye bajo la licencia MIT.

Autor
@barcevelasco
