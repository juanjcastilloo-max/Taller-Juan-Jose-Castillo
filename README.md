# Taller-Juan-Jose-Castillo
# Etapa 1: Programación Orientada a Objetos en Java

## Preguntas y respuestas

### 1. ¿Qué guarda una variable `int` y qué guarda una variable `Libro`?

La variable `int` almacena directamente un valor entero, como 8 o 20. Por otro lado, una variable de tipo `Libro` contiene una referencia que permite acceder a un objeto creado a partir de esa clase.

### 2. ¿Por qué prestar con `l2` cambió `l1` pero no `l3`?

Esto ocurre porque `l1` y `l2` hacen referencia al mismo libro. Por lo tanto, cuando se cambia su disponibilidad usando `l2`, el cambio también se refleja al consultar el objeto mediante `l1`. En cambio, `l3` representa una referencia a otro objeto, por lo que su estado permanece igual.

### 3. ¿Por qué el compilador no detectó la `NullPointerException`?

El compilador verifica la sintaxis y muchas reglas del lenguaje, pero no puede detectar todos los errores que dependen de los valores que tienen las variables durante la ejecución. Si una referencia contiene `null` y se intenta utilizar para acceder a un método o atributo, puede producirse una `NullPointerException`.

### 4. ¿Qué diferencia hay entre modificar el objeto que recibe un método y asignarle uno nuevo a su parámetro?

Cuando un método modifica un objeto, cambia su estado y ese cambio puede verse desde otras referencias al mismo objeto. Sin embargo, cuando se asigna un objeto diferente al parámetro, solamente se modifica la referencia local utilizada dentro del método. La variable original que se pasó
