# Comportamiento

El informe de comportamiento nos permite visualizar información detallada del comportamiento del contenido de nuestra web, como páginas más vistas, promedio de tiempo en la página, porcentaje de rebote, métricas de rendimiento, eventos, etc.

## Visión General

Este panel nos muestra información generales de páginas vistas, promedio de tiempo, porcentaje de rebote, porcentaje de salidas, listado de páginas vistas, etc.

## Flujo de comportamiento

Nos muestra información gráfica del comportamiento de visitas del contenido de nuestro sitio web.

## Contenido del sitio

Este panel nos muestra los contenidos vistos de nuestro sitio web. Dividido en los siguientes informes:

* Todas las páginas: Nos muestra el listado de páginas vistas.
* Desglose de contenido: Nos muestra el listado de páginas vistas desglosado por la estructura de navegación de nuestro sitio web.
* Páginas de destino: Nos muestra el listado de páginas destino cuando los usuarios ingresan a nuestro sitio web.
* Páginas de salida: Nos muestra el listado de páginas de salida cuando los usuarios terminan su sesión en nuestro sitio web.

## Velocidad del sitio

Este panel nos muestra información de las métricas de rendimiento de nuestro sitio web, como los tiempos de carga, velocidad, tiempo de usuario, etc.

* Visión general: Nos muestra información general de la carga de página del sitio web, velocidad del sitio en navegadores, país o página.
* Tiempos de página:  Nos muestra información de los tiempos de carga de las páginas del sitio web.
* Sugerencias de velocidad: Nos muestra información de  sugerencias de mejora para cada página del sitio web. Este informe esta conectado con la herramienta Google PageSpeed Insights.
* Tiempos de usuario: Nos muestra información del tiempo de carga de los usuarios para cada página. [https://www.thyngster.com/mide-los-tiempos-de-usuario-con-google-analytics/](https://www.thyngster.com/mide-los-tiempos-de-usuario-con-google-analytics/) 

## Búsquedas en el sitio

Este panel nos muestra información de las búsquedas realizadas de algún buscador interno del sitio web. Para que podamos ver datos en este panel deberemos configurar los parámetros de búsqueda desde la configuración de una vista. 

* Visión general: Nos muestra información generales de las búsquedas internas.
* Uso: Nos muestra información del uso del buscador del sitio web, como visitas que utilizan el buscador como las que no.
* Términos de búsqueda: Nos muestra información de los términos de búsqueda utilizados en el buscador.
* Páginas de búsqueda: Nos muestra las páginas de donde los usuarios han realizado búsquedas.

## Eventos

Este panel nos muestra los eventos o interacciones realizadas dentro del sitio web, como clics, reproducción de videos, descargas, etc.

Los eventos estan compuestos por: categorias, acción, etiqueta y valor. 

Para etiquetar un elemento, se debe configurar dentro del código fuente del sitio web de la siguiente forma:

```text
gtag('event', 'acción', { 'event_category': 'categoria', 'event_label': 'etiqueta', 'value': 'valor'});
```

* Visión general: nos muestra información general de todos los eventos del sitio web.
* Eventos principales: Nos muestra el listado de los eventos organizados por categoría, acción y etiqueta.
* Páginas: Nos muestra las páginas en donde se han realizados eventos.
* Flujo de eventos: Nos muestra una representación gráfica del flujo de los eventos.

## Editor

Desde este panel podremos ver la información de las publicaciones de anuncios realizadas con la herramienta Google Ad Manager. Es necesario contar con una cuenta enlazada a la herramienta Google Analytics.

Podremos ver informes como: 

* Visión general
* Páginas del editor
* URLs de referencia del editor

## Experimentos

Este informe se reemplaza por la nueva herramienta de Google Optimize.

