#Diferencias entre un IDE y un editor de texto.

>##IDE:
Un IDE (Entorno de Desarrollo Integrado) es un software que proporciona herramientas para el desarrollo de software, como autocompletado, depuración, compilador, integración con control de versiones, entre otros. Ejemplos: IntelliJ IDEA, Eclipse, Visual Studio, NetBeans.

>##Editor De Texto
Un editor de texto es una herramienta más simple que permite escribir código, pero sin características avanzadas como depuración o compilación. Ejemplos: Notepad++, Sublime Text, VS Code (aunque este último, con extensiones, puede parecer un IDE).

>#Tipos de lenguajes de programación (tipados y no tipados)
-Lenguajes tipados: Exigen declarar el tipo de dato antes de usar una variable. Ejemplo: Java, C, C++. Se dividen en:
**Tipado fuerte:** No permite conversiones implícitas entre tipos incompatibles (Java).
**Tipado débil:** Permite conversiones implícitas, a veces sin advertencias (JavaScript).

-Lenguajes no tipados: No requieren definir el tipo de dato de una variable, ya que este se asigna dinámicamente en tiempo de ejecución. Ejemplo: Python, JavaScript (aunque tiene TypeScript como alternativa tipada).

>##Tipos de datos en Java
1. Numéricos
-Enteros: byte, short, int, long (según el tamaño en bytes y el rango de valores).
-Decimales: float y double (según la precisión que manejan).
2. Cadenas
-String: Tipo de dato para representar texto. Es inmutable.
-char: Para almacenar un solo carácter.
3. Fechas
-LocalDate (solo fecha).
-LocalTime (solo hora).
-LocalDateTime (fecha y hora combinadas).
Estos pertenecen a la API de java.time, que reemplaza a la antigua Date y Calendar.