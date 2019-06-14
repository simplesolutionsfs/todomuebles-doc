.. _attribute-page-label:

Atributos / Headers
====================

Acontinuacion se explicaran todos los attributos que contiene el archivo de importe, es importante entender que cada uno de estos attributos pertenece a una columna.

.. note::
   Para iniciar la carga de contenido en el Archivo de importacion se debe destacar que hay 4 tipos de atributos.

   - **Constantes:** 
     Valores en el excel que no se deben cambiar.

   - **Requeridos:** 
     Estos son los atributos mínimos requeridos para poder hacer un importe de un producto a la tienda de todomuebles.

   - **Filtrables:** 
     Estos attributos estan atados a unas opciones posibles a las cuales se tiene que adaptar, solo se debera popular estos campos con las opciones indicadas en la tabla.

   - **Opcionales:** 
     Attributos opcionales que ir vacios no afecta el importe del archivo.

.. warning:: Todas las variaciones o agrupaciones de opciones deben ir separados por comas ( , )


.. csv-table:: Lista de atributos
   :file: ../doc/attributeList3.csv
   :widths: 10 45 10 5 30
   :header-rows: 1