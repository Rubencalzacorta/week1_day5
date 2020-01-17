# week1_day5

> JS | Data types: objects
>
> JS | Classes
>
> JS | DOM intro & selectors
>
> JS | DOM manipulation


## Main points: objects

- Los objetos de notación literal están compuestos por pares _key: value_
- En relación a las _keys_:
  - Hablamos de una **propiedad** frente a una _key_ cuyo valor es cualquier tipo de dato, excepto una función.
  - Hablamos de **método** frente a una _key_ cuyo valor es una función.
- Es posible acceder a una _key_ de un objeto, bien sea para hacer un uso _setter_ o _getter_ de la misma:
  - Mediante la notación del punto.
  - Mediante el acceso nominal mediante corchetes.
- Los operadores aplicables a objetos son:
  - El operador `in`permite conocer la existencia de una propiedad en un objeto.
  - El operador `delete` permite eliminar una propiedad de un objeto.
- Las iteraciones aplicables a objetos son:
  - El bucle `for...in` permite recorrer las _keys_ de un objeto.
  - `Object.keys(obj)` permite iterar sobre las _keys_ de un objeto.
  - `Object.values(obj)` permite iterar sobre los valores de un objeto.
 - Dentro de método de un objeto la palabra reservada `this`hace referencia al propio objeto.
 
 ## Main points: classes
 
- Las clases describen la estructura que todas sus instancias compartirán.
- Disponen de:
  - **Método constructor**: único, opcional y conectado a la instancia, donde se declaran las propiedades internas de la misma.
  - **Métodos prototype**: métodos ordinarios que dotan de capacidades a las instancias.
- La palabra reservada `extends` permite extender el alcance inicial de una clase con otra/s clase/s hijas.
- En ellas, el método `super()`permite enviar a la clase padre las propiedades relativas a la misma.

 ## Main points: DOM selectors
 
 - Los selectores DOM permiten alcanzar objetos del documento HTML desde el script:
 
 

| Nombre | Argumento | Retorno | Alcance |
| ------------- | ------------- | ------------- | ------------- |
| .querySelector() | Selector CSS | Objeto | Primer objeto que coincida con el selector |
| .querySelectorAll() | Selector CSS | NodeList | Array de objetos que coincidan con el selector |
| .getelementsByClassName() | Nombre de clase | HTMLCollection * | Array de objetos que contengan la clase argumentada |
| .getelementsByTagName() | Nombre de etiqueta | HTMLCollection * | Array de objetos que contengan la clase argumentada |
| .getelementsByName() | Valor de `name` | HTMLCollection * | Array de objetos que contengan el valor argumentado en su atributo `name` |
