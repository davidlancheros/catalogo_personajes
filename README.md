README-cliente-servidor.md Título del Proyecto Catalogo de personajes

Versionado 📌 V 1.2

Autor ✒️ David Leonardo Lancheros

El patron de diseño que en mi opinión se uso fue el abstract Factory:
debido a que proporciono una interfaz para crear familias de objetos relacionados o dependientes sin especificar sus clases concretas.
Una jerarquía que encapsula: muchas "plataformas" posibles y la construcción de una suite de "productos".

El principio de diseño que creo que es con el que se orienta la tarea es el KISSPermalink:
“Keep it simple[,] stupid”: hay discrepancias sobre si esta frase significa: “Déjalo simple, estúpido” o “Mantenlo estúpidamente simple”. Este principio establece que el código, el diseño, la documentación, todo lo relacionado con el software, debe ser tan simple como sea posible.

Los programadores tendemos a complicar las cosas. Nos piden un formulario sencillo y queremos hacer un generador de formularios que soporte este y todos los formularios en el futuro. No tenemos ni 100 usuarios y ya queremos usar Kubernetes. Necesitamos un simple binding de datos y queremos meter Angular 7, Ionic 3 y 250 bibliotecas más.

Este principio establece que:

Nuestro software en general debería tener tan pocos componentes (y por lo tanto líneas) como sea posible.
No deberíamos tener funcionalidades que no se ocupen actualmente “por si en el futuro se ocupan”.
La documentación debe tener la información estrictamente necesaria.
El código debe ser lo más obvio y sencillo posible. Se deben evitar esas líneas que sólo sirven para presumir lo inteligente que eres.
El diseño debe mantener la estructura simple, siempre que se pueda.

Tambien en mi punto de vista se usa el principio Single Responsibility (Responsabilidad Única) que nos habla sobre una entidad de software debería tener una sola responsabilidad, esto también se puede interpretar como “tener una y sólo una razón para cambiar”. En pocas palabras, tu componente/función/clase debería hacer muy bien una sola cosa.
