# WeSplit
WeSplit es una app desarrollada en SwiftUI que permite a los usuarios calcular la cantidad a pagar por persona en un grupo al dividir la cuenta de un restaurante. Los usuarios pueden ingresar la cantidad total de la cuenta, seleccionar el porcentaje de propina y especificar el número de personas entre las que se divide la cuenta.

## Características: 
- Cálculo de Propina: Ingresa la cantidad de la cuenta y elige un porcentaje de propina entre 0% y 100%.
- División por Persona: La aplicación muestra cuánto debe pagar cada persona, facilitando la gestión de las cuentas grupales.
- Uso de modificador @FocusState para manejar el enfoque del teclado, .toolbar para añadir confirmación en la barra de herramientas, Textfield junto a .currency para mostrar valor ingresado en una cantidad monetaria para el desarrollo de la app.
  
- **Gestión del enfoque del teclado**: Se implementa `@FocusState` para manejar el enfoque del teclado, lo que permite que el teclado se muestre y se oculte correctamente cuando se interactúa con los campos de texto.

- **Modificador de barra de herramientas**: Utilizando `.toolbar`, se añade un botón "Done" que permite a los usuarios cerrar el teclado fácilmente después de ingresar datos.

- **Formato de moneda**: El campo de texto (`TextField`) utiliza `.currency` para mostrar automáticamente el valor ingresado como una cantidad monetaria, adaptándose a la moneda local del usuario.

- **Control de selección**: La aplicación utiliza `Picker` para seleccionar el porcentaje de propina y el número de personas, permitiendo a los usuarios elegir entre múltiples opciones de manera intuitiva.

- **Cálculos automáticos**: Se utilizan propiedades computadas para calcular y mostrar la cantidad total a pagar y el monto por persona en tiempo real, lo que mejora la interactividad y la usabilidad.


