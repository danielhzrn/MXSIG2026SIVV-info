# MXSIG2026SIVV

MXSIG2026SIVV es un Sistema de Información Geográfica (SIG) que permite explorar **capas de manzanas catastrales** de municipios del Estado de México mediante un mapa interactivo. El visor vincula la ubicación de cada manzana con la información catastral disponible para su consulta y comparación.

## ¿Qué muestra una capa de manzanas catastrales?

Cada manzana se representa como un polígono que permite ubicarla y reconocer su contorno en el mapa. Al seleccionarla, puedes consultar los atributos disponibles, como el municipio, la clave catastral y los valores unitarios del suelo. La cobertura y los atributos disponibles dependen de la capa y del registro consultado.

## ¿Qué puedes hacer en el visor?

- **Localizar una manzana.** Activa la capa catastral del municipio que te interesa y busca la manzana o selecciónala directamente en el mapa.
- **Consultar su ficha.** Revisa la clave catastral, el valor unitario por metro cuadrado del área homogénea y, cuando estén documentados, los valores de las bandas asociadas a vialidades.
- **Comparar hasta cuatro manzanas.** Elige una como referencia y revisa las diferencias de valor unitario entre los registros con asignación documental. Puedes descargar la comparación en CSV o TXT.
- **Consultar los metadatos.** Revisa la cobertura de cada capa, las páginas del documento de origen y las ausencias de información que afectan la interpretación de los datos.

## Ejemplo de consulta

Para comparar dos manzanas, activa la capa correspondiente, agrega ambas a la comparación y elige una como referencia. La tabla muestra los valores unitarios disponibles y la diferencia respecto a la referencia cuando ambas tienen un valor asignado.

## Fuente e interpretación

Las capas se documentan con referencia a las *Tablas de Valores Unitarios de Suelo y Construcciones para el ejercicio fiscal 2026* del Estado de México. Un registro sin valor asignado indica que falta ese dato en la consulta y se excluye del cálculo de diferencias. Los valores se expresan por metro cuadrado y sirven como referencia para comparar manzanas. La valuación total de un predio y el cálculo del impuesto predial requieren información adicional.
