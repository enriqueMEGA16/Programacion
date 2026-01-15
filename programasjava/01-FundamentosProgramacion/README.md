# Actividad 2 — Reporte de Buenas Prácticas y Documentación de Código

**Alumno:** Andrus Enrique Gallegos Mendieta   
**Grupo:** 2IRD-G1  
**Fecha:** 14/01/2026
**Unidad:** X

## 1. Objetivo del reporte
El objetivo de aprender buenas prácticas de documentación de código es desarrollar la capacidad de escribir programas claros, comprensibles y fáciles de mantener, mediante el uso adecuado de comentarios y estándares de documentación. Esto permite que otros programadores, así como el propio desarrollador, puedan entender el funcionamiento del código, facilitar su mantenimiento, reducir errores y mejorar la calidad del software a lo largo del tiempo.

## 2. Buenas prácticas de codificación
### 2.1 Nombres de variables
Los nombres de las variables son fundamentales para que el código sea fácil de leer y entender. Utilizar nombres adecuados permite identificar rápidamente el propósito de cada variable y facilita el mantenimiento del programa.
- Reglas:
Usar nombres descriptivos que indiquen claramente qué información almacena la variable.

Evitar nombres genéricos como x, a o var, excepto en casos muy específicos.

Utilizar camelCase en lenguajes como Java (ejemplo: totalCompra, numeroAlumnos).

Los nombres deben iniciar con letra minúscula y no contener espacios.

Evitar abreviaturas confusas o poco claras.

Usar nombres en un solo idioma dentro del programa.

El nombre debe reflejar su función o significado, no su tipo de dato.
- Ejemplo:
int salarioMensual = 500;

### 2.2 Comentarios
- Cuándo comentar:
Cuando el código realiza una lógica compleja que no es evidente a simple vista.

Para explicar el propósito de un método, clase o función.

Al describir parámetros, valores de retorno y posibles excepciones.

Cuando una decisión de diseño no es obvia.

Para indicar restricciones, supuestos o condiciones importantes.

En bloques de código que puedan resultar difíciles de interpretar.
- Qué evitar:
No comentar línea por línea lo que ya es evidente.

Evitar comentarios que solo repitan lo que el código dice.

No usar comentarios desactualizados.

Evitar comentarios ambiguos o poco claros.

No usar comentarios para justificar malas prácticas.

Evitar lenguaje informal o poco profesional.

### 2.3 Estructura del código
- Indentación:
La identación consiste en aplicar sangrías adecuadas al código para mostrar visualmente la jerarquía y el alcance de las instrucciones. Una correcta identación permite identificar fácilmente bloques como ciclos, condicionales y métodos, reduciendo errores y mejorando la legibilidad. Mantener un estilo de identación consistente es una buena práctica esencial.
- Modularidad:
La modularidad implica dividir el programa en módulos, funciones o métodos que realicen tareas específicas. Esto permite reutilizar código, facilitar las pruebas y simplificar la documentación. Cada módulo debe tener una responsabilidad clara y estar debidamente documentado para explicar su función y uso.
- Evitar duplicidad:
La duplicidad ocurre cuando el mismo código se repite en varias partes del programa. Evitarla mejora el mantenimiento y reduce errores, ya que cualquier cambio solo se realiza en un único lugar. Para ello, es recomendable reutilizar funciones, métodos o clases, y documentar adecuadamente su propósito.

## 3. Documentación del código
### 3.1 Estándares
- Estándar elegido:
- Elementos recomendados:

### 3.2 Herramientas / enfoque
- README / generadores / extensiones:
Existen diversas herramientas que ayudan a crear y mantener la documentación del código de forma estructurada. Entre las más utilizadas se encuentran Javadoc, que permite generar documentación automática a partir de comentarios en el código Java; Markdown, empleado para documentar proyectos de manera clara y ordenada; y los entornos de desarrollo (IDE), como IntelliJ IDEA o Eclipse, que facilitan la inserción de comentarios y la organización del código. Estas herramientas estandarizan la documentación y mejoran su presentación.
- Ventajas:
Una documentación adecuada mejora la comprensión del código, reduce errores y facilita su mantenimiento. Además, permite que otros desarrolladores se integren más rápido a un proyecto, promueve el trabajo en equipo y ahorra tiempo al momento de realizar modificaciones o correcciones. También contribuye a la calidad y profesionalismo del software.

## 4. Ejemplos prácticos
### 4.1 Antes / Después (Ejemplo 1)
**Antes:**
```public double c(double a, double b) 4
    return a * b;
    txt
```

**Después**
```  @param base  Valor de la base del rectángulo
 * @param altura Valor de la altura del rectángulo
 * @return Área total del rectángulo
 */
public double calcularAreaRectangulo(double base, double altura) 
    return base * altura;
    txt
```


### 4.3 Ejemplo de documentación
/**
 * Clase que representa una calculadora básica.
 * Proporciona métodos para realizar operaciones aritméticas simples.
 */
public class Calculadora {

    /**
     * Suma dos números enteros.
     *
     * @param numero1 Primer número a sumar
     * @param numero2 Segundo número a sumar
     * @return Resultado de la suma de los dos números
     */
    public int sumar(int numero1, int numero2) {
        return numero1 + numero2;
    }
}

## 5. Recomendaciones finales
Utilizar nombres de variables, métodos y clases claros y descriptivos.

Mantener una estructura ordenada y una identación consistente en todo el código.

Documentar las partes importantes del programa usando estándares adecuados.

Evitar comentarios innecesarios o redundantes y mantener la documentación actualizada.

Aplicar modularidad para facilitar la reutilización y el mantenimiento del código.

Evitar la duplicidad de código mediante funciones o métodos reutilizables.

Revisar y probar el código antes de entregarlo para asegurar su correcto funcionamiento.

Adoptar las buenas prácticas desde el inicio del desarrollo para crear hábitos profesionales.

## 6. Fuentes consultadas
1. Oracle. (s.f.). Javadoc Tool and API Documentation. Oracle Documentation.

2. Oracle. (s.f.). Java Code Conventions. Oracle Documentation.

3. Sommerville, I. (2016). Ingeniería de Software (10.ª ed.). Pearson Educación.

4. Pressman, R. (2014). Ingeniería del Software: Un enfoque práctico (7.ª ed.). McGraw-Hill.

5. Gamma, E., Helm, R., Johnson, R., & Vlissides, J. (1995). Design Patterns: Elements of Reusable Object-Oriented Software. Addison-Wesley.

6.  GitHub. (s.f.). Mastering Markdown. GitHub Guides.