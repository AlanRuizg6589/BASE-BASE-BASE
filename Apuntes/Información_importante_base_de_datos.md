Cuando uno crea entidades, el conectar el tipo de relación no es tan simple.
Hay dos forma de la cual se pueden hacer y yo no tenia ni idea.
Relaciones en un solo momento; Relacion con un historial.

La relación en un momento es el que todos conocemos, Ocurre en ese preciso momento y ambas entidades no tienen ningun tipo de registro activo.

Ejemplo: Libro <-> Genero

No existen registro en **ninguno de los atributos**

Son exactamente en ese momento, un libro puede tener varios generos a la vez. Y un genero se puede encontrar en varios libros a la vez.

Es lo que basicamente me enseñaron.

Ahora van las relaciones historicas:

Ejemplo: ***Estacionamiento <-> vehiculo***

En este caso vehiculo tiene tiempo registrado de comienzo y de termino. Un vehiculo **puede tener varios arriendos distintos** y un estacionamiento puede tener varios arriendos del mismo vehiculo.

Es mas o menos lo que puedo explicar, es un poco complejo, per para no entrar en problemas (del cual ya me di cuenta que conectar vehiculo y estacionamiento es poblematico porque no se mantiene registro de todos los arriendos y por eso es mejor que el arriendo sea su propia entidad)

Peor el punto es que si **Tratas con un historial, hay que verlo en un lapso de tiempo completo. No es solo en un momento**
