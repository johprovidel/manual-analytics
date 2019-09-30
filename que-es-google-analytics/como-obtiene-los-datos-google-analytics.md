# Como obtiene los datos Google Analytics

Google Analytics funciona por medio de un script o bibliotecas javascript mediante la instalación de un código de seguimiento llamado gtag.js, analytics.js o ga.js. Desde estos códigos se registran distintas cookies que contiene información del usuario entre el emiso y el receptor para registrarse en Google Analytics.

El script gtag.js y analytics.js registra las siguientes cookies:

| Nombre de la cookie | Duración | Descripción |
| :--- | :--- | :--- |
| `_ga` | 2 años | Se usa para distinguir a los usuarios. |
| `_gid` | 24 horas | Se usa para distinguir a los usuarios. |
| `_gat` | 1 minuto | Se usa para limitar el porcentaje de solicitudes. Si has implementado Google Analytics mediante Google Tag Manager, esta cookie se llamará `_dc_gtm_<property-id>`. |
| `AMP_TOKEN` | 30 segundos a 1 año | Incluye un token que se puede utilizar para recuperar un ID de cliente del servicio de ID de cliente de AMP. Otros posibles valores indican inhabilitaciones, solicitudes en curso o errores obtenidos al recuperar un ID del servicio de ID de cliente de AMP. |
| `_gac_<property-id>` | 90 días | Incluye información de la campaña relativa al usuario. Si has vinculado tus cuentas de Google Analytics y Google Ads, las etiquetas de conversión de sitios web leerán esta cookie, a menos que la inhabilites. [Más información](https://support.google.com/google-ads/answer/7521212?hl=es) |



### ga.js: uso de cookies <a id="gajs"></a>

La biblioteca JavaScript ga.js usa cookies propias para:

* Determinar el dominio que se medirá
* Distinguir a los usuarios únicos
* Limitar el porcentaje de solicitudes.
* Recordar el número y la duración de las visitas anteriores
* Recordar la información de las fuentes de tráfico
* Determinar el inicio y el fin de una sesión
* Recordar el valor de las variables personalizadas de visitante

Referencia de: developers.google.com



