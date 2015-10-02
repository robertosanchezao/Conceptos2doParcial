# Conceptos2doParcial

Conceptos Segundo Parcial

Variable Estática:
	Una variable estática es aquella que se ubica estáticamente en el programa y cuyo tiempo de vida se extiende hasta que el programa deja de ejecutarse. Posee un ámbito más amplio que el de otras variables y sus valores pueden ser fijos o cambiar durante la ejecución del programa. 

Ciclo de Vida de las Variables:
	Las variables tienen distintos ciclos de vida dependiendo del tipo al que pertenezcan:
	
	Instancia (u objeto): Se crea cuando el objeto que las contiene se crea, si no se definen, se crean por defecto (null o 0) y se destruyen cuando ya no se encuentran referencias activas del objeto.
	
	Estáticas (o de clase): Se crea cuando la clase que las contiene se usa por primera vez. Se inicializan por defecto si no se definen y suelen existir para el resto del programa. 
	
	Locales (o de bloque): Se crean en la sentencia en la que están definidas; no se inicializan por defecto, ya que contienen datos imprevisibles y se destruyen al salir del bloque. 

Memoria Dinámica: 
	La memoria dinámica es aquella que se solicita en tiempo de ejecución de una variable. No puede ser definida y no se sabe el tamaño real que tendrá en tiempo de compilación. Funciona de manera que mientras más memoria necesite una variable, puede solicitar más al sistema operativo y seguir ejecutando. 

Clase:
	Una clase es un modelo o plantilla que sirve para crear objetos de un tipo específico o predefinido. Representan entidades o conceptos y cada clase define un conjunto de variables y los métodos usados para operar con ellas. Los lenguajes de programación suelen soportar distintos tipos de clases. 

Objeto:
	Un objeto es una unidad dentro de un programa que consta de un estado y de un comportamiento, que a su vez constan de datos y de tareas realizables durante el tiempo de ejecución. En programación orientada a objetos, un objeto se crea instanciado en una clase. 
Instanciación:
	La instanciación se refiere a la realización específica de una clase o prototipo determinados. 

Herencia:
	La herencia es un mecanismo que permite crear clases nuevas o subclases a partir de clases previamente diseñadas y probadas; evitando el rediseño, modificación y verificación de la parte ya implementada. La herencia implica que una subclase tiene todos los atributos y funcionalidad de una super clase. 

Sobrecarga:
	Sobrecarga es la capacidad de un lenguaje de programación de nombrar con el mismo identificador a diferentes variables u operaciones. En la programación orientada a objetos, la sobrecarga se refiere a tener dos o más funciones con el mismo nombre pero funcionalidad diferentes. 

Shadowing (Ensombrecimiento):
	Se conoce como shadowing al hecho de que una variable local y una variable miembro, pertenecientes a la misma clase, definidas en un método miembro se llamen igual. 

