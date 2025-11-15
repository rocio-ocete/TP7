# Práctico 7: Herencia y Polimorfismo en Java

Este repositorio contiene los ejercicios del **Práctico 7** de la materia de programación orientada a objetos, enfocados en **herencia, polimorfismo y uso de interfaces** en Java.

---

## Ejercicios

### Ejercicio 1: Vehículo y Auto

**Descripción:**  
Se debe crear una clase `Vehiculo` con los atributos `marca` y `modelo` y un método `mostrarInfo()`. Luego, se crea una clase `Auto` que herede de `Vehiculo` y tenga un atributo adicional `cantidadDePuertas`. Además, se sobrescribe el método `mostrarInfo()`.

**Clases involucradas:**
- `Vehiculo`
- `Auto`

**Main:**  
Se instancia un objeto de tipo `Auto` y se muestra su información completa.


---

### Ejercicio 2: Figuras y cálculo de áreas

**Descripción:**  
Crear una clase abstracta `Figura` con el atributo `nombre` y un método abstracto `calcularArea()`. Luego, crear clases `Circulo` y `Rectangulo` que implementen `calcularArea()` según su fórmula.  
Se crea un array de figuras y se muestran las áreas usando polimorfismo.

**Clases involucradas:**
- `Figura` (abstracta)
- `Circulo`
- `Rectangulo`

**Main:**  
Instanciar al menos un círculo y un rectángulo, agregarlos al array y mostrar el área de cada figura.


---

### Ejercicio 3: Empleados y cálculo de sueldos

**Descripción:**  
Crear una clase `Empleado` con un método `calcularSueldo(Empleado e)` que devuelva un sueldo fijo según el tipo de empleado.  
Se crean dos subclases: `EmpleadoPlanta` y `EmpleadoTemporal`.  
Se recorre una lista de empleados y se calcula el sueldo usando `instanceof`.

**Clases involucradas:**
- `Empleado`
- `EmpleadoPlanta`
- `EmpleadoTemporal`

**Main:**  
Agregar instancias de ambas subclases a la lista y calcular el sueldo de cada empleado.


---

### Ejercicio 4: Animales y sonidos

**Descripción:**  
Crear una clase `Animal` con métodos `hacerSonido()` y `describirAnimal()`.  
Crear subclases `Perro`, `Gato` y `Vaca`, sobrescribiendo `hacerSonido()` con `@Override`.  
Se utiliza polimorfismo para mostrar los sonidos de cada animal.

**Clases involucradas:**
- `Animal`
- `Perro`
- `Gato`
- `Vaca`

**Main:**  
Agregar instancias de cada animal a una lista y mostrar sus sonidos.


---

### Ejercicio 5: Pagos y polimorfismo con interfaces

**Descripción:**  
Crear una interfaz `Pagable` con un método `pagar()`.  
Crear clases que implementen esta interfaz: `TarjetaCredito`, `Transferencia` y `Efectivo`.  
Se define un método `procesarPago(Pagable medio)` que permite procesar cualquier forma de pago de manera genérica.

**Clases involucradas:**
- `Pagable` (interfaz)
- `TarjetaCredito`
- `Transferencia`
- `Efectivo`

**Main:**  
Instanciar objetos de las distintas clases de pago y procesarlos usando una única función.

Autor: Rocio Milagros Ocete GitHub: rocio-ocete Comisión 3
