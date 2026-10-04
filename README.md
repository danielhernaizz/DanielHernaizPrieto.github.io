# Calculadora Avanzada - Tecnologías Móviles y Web
**Alumno:** Daniel Hernaiz Prieto

🔗 **Enlace a la calculadora funcional:** [https://danielhernaizprieto.github.io](https://danielhernaizprieto.github.io)

## Funcionalidades Implementadas
Esta calculadora web ha sido desarrollada utilizando HTML, CSS y JavaScript vanilla, cumpliendo con los requisitos mínimos y las ampliaciones propuestas en la práctica:

* **Operaciones Unarias:** Cálculo de la elevación al cubo (x³), valor absoluto/módulo (|x|), factorial (x!) y raíz cuadrada (√x).
* **Operaciones Binarias:** Suma, resta, multiplicación, división (con validación para evitar dividir por cero) y potencias (xʸ).
* **Operaciones con Listas (CSV):** Procesamiento de valores numéricos separados por comas para sumar sus elementos, calcular la media, ordenarlos de menor a mayor, invertir su orden y eliminar el último valor introducido. El procesado ignora de forma segura espacios en blanco y comas sueltas.
* **Campo de Información Dinámico:** Panel interactivo que notifica al usuario sobre el éxito de las operaciones, muestra instrucciones sobre el siguiente paso en operaciones binarias y clasifica los resultados de operaciones unarias.
* **Gestión de Errores:** Validación robusta que previene y avisa sobre entradas vacías, introducción de texto en listas numéricas CSV, intentos de calcular raíces de números negativos o factoriales de decimales/negativos, inyectando un formato visual de alerta (texto rojo).
* **Accesibilidad (UX):** Soporte de uso mediante teclado permitiendo ejecutar la operación de resolución pulsando la tecla "Enter".
