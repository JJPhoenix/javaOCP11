# Welcome to Java

#### Objetivos del capítulo

- Entender las tecnologías y entornos:
  - Describir las tecnologías y los entornos de Java.
  - Identificar las características principales del lenguaje Java.
- Crear un programa simple:
  - Crear un ejecutable Java con una **clase main**.
  - Compilar y ejecutar un programa Java desde la línea de comandos.
  - Importar paquetes (**import packages**).
- Describir y usar Objetos y Clases:
  - Definir la estructura de Java.

## **Principal componente**

El **JDK** (Java Development Kit) contiene lo mínimo necesario para desarrollar en Java:

| Tecnología | Detalle |
|:-----------|:--------|
| javac      | Compilador de Java para generar los archivos `.class` a partir de los archivos `.java`. |
| java       | Herramienta que crea una máquina virtual y ejecuta el programa. |
| jar        | Empaqueta los archivos en un archivo `.jar`. |
| javadoc    | Comando para generar documentación. |

- Java contiene una lista de API (Application Programming Interfaces) que se pueden usar.

### **Beneficios de Java**

a. **Lenguaje orientado a objetos:** Todo el código está definido en clases y estas clases pueden ser instanciadas en objetos. **No es procedimental** (rutinas o métodos pero no clases). Java permite **programación funcional** dentro de una clase, pero la orientación a objetos es la principal.

b. **Encapsulación:** Tiene modificadores para proteger datos y controlar el acceso.

c. **Plataforma independiente:** Es un lenguaje interpretado, compila una vez pero no necesita recompilarse en otros sistemas operativos. "Escribe una vez, ejecuta donde quieras." La portabilidad permite compartir fácilmente piezas de software.

d. **Robusto:** Una de sus principales ventajas es el manejo óptimo de memoria. Java administra la memoria con su propio garbage collector.

e. **Simple:** Java fue diseñado para ser simple y más fácil de entender que C++.

f. **Seguridad:** Java se ejecuta dentro de la JVM.

g. **Multihilos:** Está diseñado para permitir que múltiples piezas de código se ejecuten al mismo tiempo. Muchos APIs facilitan estas tareas.

## Entendiendo la estructura de las clases en Java

- Las clases son los bloques principales del programa.
    - Describen todas las partes y características de algún objeto o concepto.
- Los objetos son creados a partir de las clases. Son instancias en tiempo de ejecución (*runtime*).
    - Se les conoce como **instancias**.
    - Cada objeto es una representación única de una clase y representa un estado del programa.
- Una referencia es una variable que apunta al objeto creado.