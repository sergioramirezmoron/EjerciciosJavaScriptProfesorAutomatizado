### Ejercicios Prácticos de JavaScript
#### Ejercicio 1: Mapear Números con Función Personalizada
Crea una función que tome un array de números y una función personalizada como argumentos. La función debe aplicar la función personalizada a cada elemento del array y devolver un nuevo array con los resultados. Por ejemplo, si la función personalizada es `Math.sqrt`, el array `[1, 4, 9]` debería devolver `[1, 2, 3]`.

#### Ejercicio 2: Combinar Objetos con Propiedades Únicas
Escribe una función que combine dos objetos en uno solo, asegurándose de que solo se incluyan propiedades únicas. Si una propiedad se repite en ambos objetos, debe ser incluida solo una vez en el objeto resultante. Por ejemplo, combinar `{a: 1, b: 2}` y `{b: 3, c: 4}` debería devolver `{a: 1, b: 3, c: 4}`.

#### Ejercicio 3: Extraer Propiedades Específicas de un Objeto
Define una función que tome un objeto y un array de propiedades como argumentos. La función debe devolver un nuevo objeto que contenga solo las propiedades especificadas en el array. Si una propiedad no existe en el objeto original, debe ser omitida en el nuevo objeto. Por ejemplo, extraer `['nombre', 'edad']` de `{nombre: 'Juan', edad: 30, ocupacion: 'Ingeniero'}` debería devolver `{nombre: 'Juan', edad: 30}`.