### Ejercicios Prácticos de Destructuring de Objetos
#### Ejercicio 1: Extraer Propiedades de un Objeto
Dado el siguiente objeto:
```javascript
const empleado = {
  nombre: "Pedro",
  edad: 35,
  cargo: "Ingeniero"
};
```
Utiliza la desestructuración para extraer las propiedades `nombre` y `edad` en variables separadas. Después, crea un objeto con dichas propiedades y los valores obtenidos.

#### Ejercicio 2: Extraer Propiedades Anidadas
Dado el siguiente objeto:
```javascript
const direccion = {
  calle: "Calle Principal",
  ciudad: "Ciudad Ejemplo",
  codigoPostal: "12345",
  ubicacion: {
    latitud: 40.7128,
    longitud: -74.0060
  }
};
```
Utiliza la desestructuración para extraer la propiedad `latitud` en una variable llamada `coordenadaX` y la propiedad `longitud` en una variable llamada `coordenadaY`.

#### Ejercicio 3: Extraer Propiedades con Nombres Diferentes
Dado el siguiente objeto:
```javascript
const producto = {
  id: 1,
  nombre: "Producto A",
  precio: 10.99,
  caracteristicas: {
    peso: 1.5,
    dimensiones: "10x10x10"
  }
};
```
Utiliza la desestructuración para extraer las propiedades `nombre` y `precio` en variables separadas. Además, extrae la propiedad `peso` y asignala a una variable llamada `pesoProducto`.