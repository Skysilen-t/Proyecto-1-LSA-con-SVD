# Proyecto de LSA-con-SVD

## Integrantes de nuestro Grupo
| Nombre | Mail UC |
| :-: | :-: |
| Drawin Zambrano | de.zambranoc@estudiante.uc.cl |
| Nahuel Gutierrez | sky@estudiante.uc.cl |


<div align="center">
  <h1>Análisis Semántico Latente (LSA) mediante SVD</h1>
  <p><i>Implementación de descomposición matricial para el análisis de estructuras semánticas en corpus de texto.</i></p>
</div>

<hr />

<h2>Descripción del Proyecto</h2>
<p>
  Este proyecto tiene como objetivo principal realizar un <b>Análisis Semántico Latente (LSA)</b> utilizando la técnica de <b>Descomposición en Valores Singulares (SVD)</b>. 
  La metodología se basa en representar una colección de documentos como una matriz de términos, aplicar SVD para reducir su dimensionalidad conservando las componentes principales y, finalmente, interpretar esta representación reducida como una aproximación de la estructura semántica latente del corpus.
</p>

<h2>Estructura del Repositorio</h2>
<pre>
.
├── 📁 Informe
│   └── 📄 informe.pdf          # Documentación teórica y análisis de resultados.
├── 📁 Proyecto
│   ├── 📓 Proyecto_lsa_con_svd.ipynb   # Notebook con el desarrollo del código.
│   └── 📁 Datos
│       └── 📄 bbc_data.csv     # Dataset original utilizado (BBC News).
└── 📄 README.md                # Descripción general del proyecto.
</pre>

<h2>Librerías Necesarias</h2>
<p>El proyecto está desarrollado en Python y requiere las siguientes dependencias:</p>
<ul>
  <li><b>scikit-learn:</b> Para la implementación de SVD y procesamiento de matrices.</li>
  <li><b>matplotlib:</b> Para la visualización de resultados y gráficas.</li>
  <li><b>pandas:</b> Para la manipulación y carga del dataset.</li>
  <li><b>numpy:</b> Para operaciones de álgebra lineal computacional.</li>
  <li><b>spacy:</b> Para el procesamiento de lenguaje natural (NLP) y tokenización.</li>
</ul>

<h2>Configuración e Instalación</h2>
<p>Sigue estos pasos para preparar tu entorno local e instalar todas las dependencias:</p>

<ol>
  <li>Instala las librerías necesarias mediante pip:</li>
</ol>

<pre><code>python -m pip install scikit-learn matplotlib pandas numpy spacy</code></pre>

<ol start="2">
  <li>Descarga el modelo de lenguaje en inglés de <b>spacy</b> (obligatorio para el procesamiento de texto):</li>
</ol>

<pre><code>python -m spacy download en_core_web_sm</code></pre>

<h2>Resumen del Análisis</h2>
<p>
  El análisis se enfoca en el dataset <code>bbc_data.csv</code>, permitiendo identificar patrones temáticos ocultos mediante la reducción de ruido y la extracción de conceptos clave a partir de la frecuencia de términos. Los detalles técnicos y las conclusiones se encuentran en el archivo PDF dentro de la carpeta <code>Informe</code>.
</p>

<hr />
<div align="center">
  <p>Desarrollado como parte de un estudio de Procesamiento de Lenguaje Natural.</p>
</div>