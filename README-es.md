# volvelle

Según la wikipedia un volvelle es un tipo de construcción de papel con piezas móviles. Los volvelles se consideran una de las formas más primitivas de computación analógica.

En este proyecto se han considerado tres subproyectos.

## Volvelle General

Intenta ser la solución más completa.Está basada en imágenes svg transparentes, busca entender y ajustar los orígenes, puntos de rotación y otros parámetros del CSS usado en el código.

## Volvelle Apianus

La idea fue sacada de una página web de el Museo de Wales donde ofrecen un PDF que contiene un escaneado con una proyección directa de un volvelle de Apiano.


## Volvelle Astronomicum Caesareum

Surge de las fotos de la restauración de este libro en la BUS.

Comprendido el proceso por los dos subproyectos anteriores la tarea más tediosa ha sido preparar las imagenes que componen el motivo.

1. Hemos utilizado GIMP.
2. Se abre la imagen en GIMP y vemos que todas ellas tienen cierta distorsión por la perspectiva usada en las fotos.
3. Separamos cada una de las imágenes.
4. Ponemos un fondo transparente, añadimos una capa transparente sobre la que dibujamos una circunferencia perfecta, y la mandamos al fondo.
5. Con la herramienta de perspectiva vamos ajustando la imagen para que el volvelle se ajuste a esta circunferencia 1:1, guardamos el fichero.
6. Incluimos este círculo en un cuadrado perfecto de proporciones 1:1 y hacemos transparentes las partes que no son del volvelle.
7. Ajustamos en la aplicación hasta conseguir las rotaciones deseadas.


