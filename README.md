
El patrón de diseño Factory es un patrón de creación que se utiliza para encapsular la creación de objetos dentro de una clase. 
Su objetivo principal es proporcionar una interfaz para crear objetos de una familia relacionada sin especificar su clase concreta. 

En TypeScript, este patrón se puede implementar de varias maneras, pero comúnmente se utiliza un Factory Method o un Abstract Factory.

Factory Method (Método de Fábrica):

En este enfoque, se define un método en una clase base (o interfaz) para crear objetos, pero se delega la creación de instancias concretas a las subclases.
Permite que las subclases alteren el tipo de objetos que se crean.
Es útil cuando la lógica de creación de objetos puede variar entre diferentes subclases.

Abstract Factory (Fábrica Abstracta):

Este patrón proporciona una interfaz para crear familias de objetos relacionados o dependientes sin especificar sus clases concretas.
Define una interfaz para la creación de objetos que debe ser implementada por las subclases.
Permite la creación de objetos relacionados sin acoplar el código cliente a las clases concretas.