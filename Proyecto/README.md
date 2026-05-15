<div align="center">
  <h2>Entorno de Desarrollo y Código Fuente</h2>
  <p><i>Implementación práctica de LSA con SVD en Python</i></p>
</div>

<hr />

<h3>Estructura de esta carpeta</h3>
<pre>
.
├── 📓 Proyecto_lsa_con_svd.ipynb   # Jupyter Notebook principal.
└── 📁 Datos
    └── 📄 bbc_data.csv             # Dataset de noticias de la BBC.
</pre>

<h3>Descripción de los Archivos</h3>

<h4>1. El Notebook (<code>Proyecto_lsa_con_svd.ipynb</code>)</h4>
<p>
  Este es el núcleo técnico del proyecto. En este cuaderno de Jupyter encontrarás el código paso a paso documentado. Las etapas principales que cubre son:
</p>
<ul>
  <li>Carga y limpieza de datos (preprocesamiento de texto usando <b>spacy</b>).</li>
  <li>Creación de la matriz término-documento.</li>
  <li>Aplicación de SVD (mediante <b>scikit-learn</b>) para la reducción de dimensionalidad.</li>
  <li>Visualización e interpretación de las componentes principales obtenidas.</li>
</ul>

<h4>2. Los Datos (<code>Datos/bbc_data.csv</code>)</h4>
<p>
  Contiene el corpus de texto utilizado para el análisis. Corresponde a una colección de artículos de la BBC, ideal para tareas de Procesamiento de Lenguaje Natural debido a su rica estructura semántica y variedad de categorías.
</p>

<h3>¿Cómo ejecutar este código?</h3>
<ol>
  <li>Asegúrate de haber instalado todas las dependencias listadas en el <b>README principal</b> (ubicado en la raíz del repositorio).</li>
  <li>Verifica que el modelo de idioma de spacy (<code>en_core_web_sm</code>) esté descargado.</li>
  <li>Inicia Jupyter Notebook o Jupyter Lab en tu terminal: <code>jupyter notebook</code></li>
  <li>Abre <code>Proyecto_lsa_con_svd.ipynb</code> y ejecuta las celdas de forma secuencial.</li>
</ol>