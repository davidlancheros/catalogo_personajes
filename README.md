README-catalogo_personajes.md

Título del Proyecto Catalogo de personajes

Versionado 📌 V 1.3

Autor ✒️ David Leonardo Lancheros

El patron de diseño que se uso fue el Decorador o Decorator:

La utilidad principal del patrón Decorator en este ejemplo, es la de dotar de funcionalidades dinámicamente a objetos mediante composición. Es decir, vamos a decorar los objetos para darles más funcionalidad de la que tienen en un principio.

Esto es algo verdaderamente útil cuándo queremos evitar jerarquías de clases complejas. La herencia es una herramienta poderosa, pero puede hacer que nuestro diseño sea mucho menos extensible. 

![imagen](https://user-images.githubusercontent.com/37816530/115420574-de483900-a1c0-11eb-9674-66dc38a2114d.png)


Propósito

Decorator es un patrón de diseño estructural que te permite añadir funcionalidades a objetos colocando estos objetos dentro de objetos encapsuladores especiales que contienen estas funcionalidades.
![imagen](https://user-images.githubusercontent.com/37816530/115420296-a3460580-a1c0-11eb-8535-298e2077af26.png)


Solución

Cuando tenemos que alterar la funcionalidad de un objeto, lo primero que se viene a la mente es extender una clase. No obstante, la herencia tiene varias limitaciones importantes de las que debes ser consciente.

    La herencia es estática. No se puede alterar la funcionalidad de un objeto existente durante el tiempo de ejecución. Sólo se puede sustituir el objeto completo por otro creado a partir de una subclase diferente.
    Las subclases sólo pueden tener una clase padre. En la mayoría de lenguajes, la herencia no permite a una clase heredar comportamientos de varias clases al mismo tiempo.

Una de las formas de superar estas limitaciones es empleando la Agregación o la Composición 

en lugar de la Herencia. Ambas alternativas funcionan prácticamente del mismo modo: un objeto tiene una referencia a otro y le delega parte del trabajo, mientras que con la herencia, el propio objeto puede realizar ese trabajo, heredando el comportamiento de su superclase.

Con esta nueva solución puedes sustituir fácilmente el objeto “ayudante” vinculado por otro, cambiando el comportamiento del contenedor durante el tiempo de ejecución. Un objeto puede utilizar el comportamiento de varias clases con referencias a varios objetos, delegándoles todo tipo de tareas. La agregación/composición es el principio clave que se esconde tras muchos patrones de diseño, incluyendo el Decorator. A propósito, regresemos a la discusión sobre el patrón.
