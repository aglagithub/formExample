## Propiedades de < frame>
| Property    | Description |
| ----------- | ----------- |
|**acceptCharset**|Establece o devuelve el conjunto de caracteres que serán utilizados para la recepción o envío del formulario. Si el atributo no está establecido o está vacio, el conjunto de carcateres será el que defina la codificación de la página donde se encuentre|
|**action**|Indica a donde se van a enviar los datos del formulario. Si el atributo no está estlecido o atá vacio, la acción del fromulario será llamarse a sí mismo.|
|**autocomplete**| Indica al navegador puede o no recuperar los valores anteriormente introducidos por el usuario. Por defecto esta activado 
|**enctype**| Indica como se deben codificar los datos antes de ser enviados al servidor. Por defecto, su valore es **application/x-www-form-urlencoded**. Lo que significa que todos los datos del formulario se codificacomo si fueran URLs, sin embargo admite los valoes de **multipart/formdata**(envio de datos sin codificar) y **plain-text** (que solo convierte losespecios a '+'|
|**length**|Devuelve el número de elementos que tiene el formulario|
|**method**|Establece o devuelve el método por el que se realizará el envío del formulario. Sus posibles valores son **GET** o **POST** |
|**name**|Indica el nombre del formulario|
|**noValidate**|Indica si el formulario debe validarse antes de ser enviado. sus valsores son **true** or **salse**|
|**target**|Indica donde debe mostrase la respuesta tras el envio del formulario al servidor. Habitualmente sus valores son **_bank** (apra indicar que se abra en una nueva ventana y **_self** (para indicar que se abra en la misma entana). Por defecto su valor es **_self**|
## Propiedades de los elementos de formulario
| Property    | Description |
| ----------- | ----------- |
|**autofocus**|Elemento que debe tener el foco cuando se carga o reinicia la página|
|**checked**|Specifies that an input field should be pre-selected when the page loads. Valid for types: **checkbox** or **radio**|
|**disabled**|Elemento desactivado. propiedad Válida para todos los elementos del formulario|
|**form**| formulario al que pertenece que el elemento pueda encontrase fuera del ambito de declaración del mismi. propiedad Válida para todos los elementos del formulario|
|**id**| Indica el ID, Deberia ser unica para cada elemento. Válida para todos los elementos del formulario y HTML|
|**list**| Elemento vinculado a una lista predefinida indicada por elemento **datalist**.Solo valida para **input**|
|**max**|Número máximo que pueede tomar el elemento. Válida para imputs de los tipos: **range, number, date, datetime-local, moth, time y week**|
|**min**|Número mínimo que pueede tomar el elemento. Válida para imputs de los tipos: **range, number, date, datetime-local, moth, time y week**|
|**maxlength**|Longitud máxima de caracteres. Válida para **input** y **textarea**|
|**minlength**|Longitud mínima de caracteres. Válida para **input** y **textarea**|
|**multiple**|El elemento puede tomar más de un valor. Válida para los elementos input: **email** y **file** y, para el elemento **select**|
|**name**|nombre del elemento, deberia se único. Válida para todos los elementos del formulario|
|**pattern**|Expresion regular para validar la entrada. Válida para inputs tipo **text, search, url, tel, email, prassword**|
|**placeholder**|texto de ayuda o una sugerencia de valor que se muestra cuando al elemento no se llenado con ningún valor. Válida para inputs tipo **text, search, url, tel, email, prassword**|
|**readonly**|Indica que el elemento se encuantra en modo de solo lectura. Válida para todos los elementos de formulario|
|**required**|Elemento obligatorio. Válida para todos los elementos de formulario|
|**selectionStart**| Posición inicial para el texto seleccionado. Valida para elementos que oermitan la edición de texto|
|**selectionEnd**|Posición final para el texto seleccionado. Valida para elementos que oermitan la edición de texto|
|**size**|Tamaño en caracteres del elemento. Válida para todos los elementos de tipo input|
|**step**|Tamaño de inreementos o decrenetos cunado se pulsan los botónes para el efecto. **range, number, date, datetime-local, moth, time y week** |
|**type**|tipo de elemento. Válida para todos los tipos de **input**|
|**value**|Valor inicial del elemento. Aplica a todos los elementos de formulario|