# **Tercer Fuego**

## Índice
1. [Motivaciones](#motivaciones)
2. [Objetivos](#objetivos-)
3. [Tecnologías](#tecnologías-%EF%B8%8F)
4. [Descripción de las columnas](#Descripción-de-las-columnas-)


# Motivaciones

En el dinámico y competitivo mundo del comercio electrónico, disponer de una base de datos robusta y precisa es fundamental para la toma de decisiones informadas y el desarrollo de estrategias efectivas. Este proyecto se centra en la creación de una base de datos de productos de cerámica, recopilada mediante técnicas de scraping desde diversas tiendas en línea especializadas en cerámica.
La cerámica, con su rica historia y diversidad de estilos, es un sector que abarca desde lo artesanal hasta la producción industrial, con una amplia gama de productos que incluyen desde vajillas y objetos decorativos hasta revestimientos y piezas de arte. Capturar esta variedad y disponibilidad de productos en una base de datos estructurada permitirá un análisis del mercado, la comparación de precios y características, y el monitoreo de la oferta y demanda.
El proceso de scraping de datos implica la extracción automatizada de información de sitios web, transformando datos no estructurados en un formato utilizable y accesible. Este proyecto utilizará herramientas y técnicas de scraping para recopilar datos de múltiples tiendas de cerámica en línea, asegurando la obtención de información precisa y actualizada. La base de datos resultante contendrá detalles esenciales como nombres de productos, descripciones, precios, materiales, y disponibilidad, entre otros atributos relevantes.
La implementación de este proyecto proporcionará una herramienta valiosa para minoristas y consumidores interesados en el mercado de la cerámica. Además, permitirá el desarrollo de aplicaciones analíticas y predictivas, aportando valor a través de insights profundos y estrategias basadas en datos. Con este esfuerzo, se busca no solo capturar la riqueza del mundo de la cerámica, sino también abrir nuevas posibilidades de análisis y comercialización en este sector en constante evolución.

## Objetivos 🚀 

1. **Scraping de Datos**: recopilación sistemática de datos de productos de cerámica desde diversas tiendas en línea especializadas. Utilizaremos técnicas de scraping para obtener información detallada sobre los productos disponibles, incluyendo precios, descripciones y otras características relevantes.
2. **Limpieza y tratamiento de los datos**: Una vez recopilados los datos, se llevará a cabo un proceso riguroso de limpieza y tratamiento. Esto implica revisar y normalizar los datos extraídos para garantizar su coherencia y calidad. También se aplicarán técnicas de limpieza asegurando que los datos sean adecuados para análisis y modelado subsiguientes.
3. **Creación de la Base de Datos**: los datos limpios y tratados se estructurarán y almacenarán en una base de datos adecuada. Se diseñará un esquema de base de datos eficiente para almacenar información detallada sobre cada producto de cerámica, facilitando su acceso y gestión para futuros análisis y consultas.
4. **Entrenamiento de IA**:  desarrollar un modelo de inteligencia artificial robusto para realizar predicciones y previsiones de mercado basadas en los datos recopilados. Utilizando técnicas de machine learning y análisis predictivo, se entrenará un modelo que pueda anticipar tendencias y comportamientos en el mercado de productos de cerámica, proporcionando insights valiosos para decisiones estratégicas y comerciales.

## Tecnologías 🛠️

### Lenguajes de Programación
**Python:** Se utiliza principalmente para el scraping de datos de diversas tiendas en línea debido a su flexibilidad y las numerosas bibliotecas disponibles para el procesamiento de datos. También es el lenguaje principal para el desarrollo del modelo de inteligencia artificial debido a su robustez en machine learning y análisis de datos.

**SQL:** Es esencial para la gestión y manipulación eficiente de la base de datos donde se almacenan los datos recopilados. Permite realizar consultas avanzadas, actualizaciones y mantenimiento de la integridad de los datos.

### Frameworks y Librerías
**Selenium:** Utilizado específicamente para el scraping de datos desde tiendas en línea, Selenium facilita la automatización del navegador para interactuar con el contenido web dinámico y extraer información estructurada de manera sistemática.

**Pandas:** Esencial para la manipulación y análisis de datos en Python. Pandas ofrece estructuras de datos flexibles y herramientas de análisis que facilitan tareas como limpieza de datos, transformaciones y agregaciones.

**Scikit-learn:** Biblioteca fundamental en Python para machine learning. Scikit-learn proporciona herramientas simples y eficientes para el análisis predictivo y la modelización de datos, incluyendo clasificación, regresión, clustering y preprocesamiento de datos.

### Herramientas
**Visual Studio Code:** Entorno de desarrollo integrado (IDE) ampliamente utilizado para programación. Visual Studio Code ofrece características necesarias como resaltado de sintaxis, depuración integrada, control de versiones integrado con Git, extensiones para Python y soporte para Jupyter Notebookss.

**Jupyter Notebook:** Se utiliza para la exploración interactiva y análisis detallado de datos. Jupyter Notebook permite combinar código, visualizaciones y documentación en un solo documento, facilitando la colaboración y la comunicación de los resultados del análisis.

**Git:** Herramienta crucial para el control de versiones del código fuente del proyecto. Git facilita la colaboración entre equipos de desarrollo, el seguimiento de cambios en el código y la gestión de ramas para el desarrollo simultáneo de funcionalidades.

**MySQL:** Utilizado para la gestión de la base de datos, MySQL es un sistema de gestión de bases de datos relacional que permite almacenar, organizar y acceder a los datos de manera eficiente y segura. Es una herramienta clave para asegurar la integridad y disponibilidad de los datos recopilados y tratados.

## Descripción de las columnas 💾
**Categoría:** Esta columna incluye el grupo principal en el que se clasifican los productos. Las categorías agrupan productos con características o usos similares, facilitando la organización y búsqueda dentro del conjunto de datos. Ejemplos de categorías podrían ser "Arcillas", "Herramientas", "Equipos", etc. Cada categoría contiene varias subcategorías.

**Subcategoría:** Proporciona un segundo nivel de clasificación dentro de las categorías principales. Las subcategorías ayudan a diferenciar los productos con más precisión. Por ejemplo, dentro de la categoría "Arcillas", las subcategorías podrían ser "Arcilla de baja temperatura" o "Arcilla de alta temperatura".

**Nombre:** Esta columna contiene el nombre específico de cada producto. El nombre puede incluir características adicionales que describen el producto más detalladamente, como su color, forma, o cualquier otra especificación relevante. Por ejemplo, "Arcilla roja con chamota 5 kg".

**Precio:** Representa el precio de cada producto. Esta columna es crucial para análisis de costo y para realizar comparaciones entre productos similares. Los precios están expresados en € e incluyen el IVA.

**url:** Almacena la URL del sitio web donde se puede acceder directamente a la página del producto. Esta información es útil para verificar detalles adicionales del producto.

**Tienda:** Indica la tienda o proveedor donde se puede encontrar cada producto. Esto puede incluir el nombre de tiendas físicas, tiendas en línea, o distribuidores específicos. Facilita el rastreo del origen de los productos.

**Peso:** Incluye los diferentes pesos disponibles para los productos y sus unidades de medida (kilogramos - Kg, o gramos - gr). Esta información es vital para productos vendidos en diferentes tamaños y para análisis de cantidades disponibles.

**Chamota:** Especifica si la arcilla tiene chamota o no. Esta columna es importante para ceramistas que necesitan especificaciones exactas del material.

**Tipo:** Almacena el tipo de arcilla u otro material, proporcionando información adicional sobre la composición o uso del producto. Por ejemplo, puede diferenciar entre "Gres", "Porcelana", etc.

**Capacidad:** Incluye los volúmenes disponibles para los productos y sus unidades de medida (litros - L, o mililitros - ml). Esto es relevante para productos líquidos o semi-líquidos y ayuda en el análisis de las cantidades disponibles. 

**Tamaño:** Proporciona las dimensiones de los productos, ya sea unidimensionales (longitud), bidimensionales (superficie), o tridimensionales (volumen). Las unidades de medida pueden variar (centímetros - cm, metros - m, etc.). Esta información es crucial para productos cuya funcionalidad depende de su tamaño específico.


