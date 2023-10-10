# datasetModa

Exploración, Análisis, Visualización y Machine Learning en datos de la Industria de la Moda

Contexto: La industria del comercio electrónico (e-commerce) en el ámbito de la moda nos presenta un escenario altamente competitivo con un crecimiento exponencial a nivel mundial debido al gran conjunto de datos que espera ser extraído e investigado. En este contexto, resulta esencial comprender los patrones de comportamiento de los consumidores mediante la exploración, análisis y visualización de productos de moda seleccionados. Mediante diversas plataformas digitales y redes sociales se ha transformado la experiencia del cliente pero además esto ha revolucionado la industria de la moda misma llevando a una gran necesidad de explorar sus nuevas tendencias, productividad, y por lo tanto, futuros desarrollos. Es así que la ciencia de datos puede cumplir un rol central en la industria de la moda para comprender la evolución y las tendencias de la misma.
Interes de la investigación: el objetivo principal de este proyecto (compuesto de 8 secciones) es comprender los patrones predominantes de los productos de moda seleccionados y así optimizar la experiencia de los usuarios. En otras palabras, el proyecto no solo tiene interés en los productos de moda y diseño en cuanto tales sino, ante todo, en la optimización de los productos seleccionados por los consumidores para comprender la evolución de los mismos y la predicción de precios futuros. El dataset incluye las siguientes columnas relevantes:

    product_id: esta es la clave única que permite identificar al producto dentor del catálogo.

    gender: esta categoría permite clasificar (target) el producto de acuerdo a tres tipos de clasificadores, femenino, masculino y unisex.

    masterCategory: se trata de una categoría primaria que distingue al producto de acuerdo a su función, sus parámetros son los siguientes: apparel (vestimenta), accesories (accesorios), footwear (calzados), personal care (fragancias).

    subCategory: se trata de una categoría secundaria, que depende de la anterior, y en la que se distingue al producto en una categoría un poco más específica, por ejemplo, dentro de vestimentas (apparel), esta columna especifica si se trata de un topwear (ropa zona-superior), bottomwear (ropa zona-inferior), innerwear (ropa interior), etc.

    articleType: es una categoría dependiente de las dos anteriores, con una clasificación aún más específica respecto al tipo de producto. Por ejemplo, dentro de vestimentas (apparel) y a su vez dentro de topwear (ropa zona-superior) esta categoría especifica si se trata de una remera (t-shirt), un top, un pullover (sweatshirts), y otros.

    baseColour: especifica el color del producto

    season: especifica a qué temporada de la moda está dirigido.

    year: especifica el año al que pertenece

    usage: especifica el tipo de uso, si es casual, deportivo, etc.

    productDisplayName: se trata del nombre con el que se presenta el producto en la plataforma de venta online.

    price: se especifica el precio en dólares.

Condición de la Base de Datos:

Esta base de datos es una muestra (2.131 registros) realizada a partir de una población de más de 44 mil datos. Adicionalmente se ha agregado una tabla de precios (en dólares) con el fin de contar con dos tablas numéricas, la otra corresponde al año que ya venía incorporada a la base de datos original.
Fuente de datos:

https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small
