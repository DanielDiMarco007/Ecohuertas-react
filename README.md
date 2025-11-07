# Ecohuertas-react

##  Flujo de datos unidireccional

En **React**, el flujo de datos es **unidireccional**, es decir, la información viaja **desde los componentes padres hacia los hijos** mediante *props*.
En **EcoHuertas**, este principio se aplica pasando datos como el nombre de las plantas, su estado o las acciones de cultivo desde un componente contenedor principal hacia los subcomponentes.
Esto garantiza una estructura más predecible y facilita el mantenimiento, ya que el flujo de la información siempre tiene una dirección clara.

---

##  Rol del estado (`useState`) y su influencia en el renderizado

El hook **`useState`** se utiliza para manejar información dinámica dentro de los componentes.

Cada vez que el estado cambia, **React vuelve a renderizar** el componente que depende de ese estado, actualizando solo las partes necesarias del DOM.
Esto hace que la interfaz sea **reactiva y eficiente**, sin necesidad de manipular el DOM manualmente.

---

##  Importancia de separar la UI en componentes reutilizables y puros

Dividir la interfaz en **componentes reutilizables** permite:

* Mantener el código más ordenado y fácil de entender.
* Reutilizar elementos comunes (botones, tarjetas, encabezados) en diferentes partes del proyecto.
* Reducir errores y mejorar la escalabilidad.

Los **componentes puros** (aquellos que dependen solo de sus props y no tienen efectos secundarios) son más predecibles y fáciles de probar.


---

##  Ventajas del JSX declarativo frente al DOM imperativo

Usar **JSX declarativo** significa describir **qué queremos que se muestre**, y no **cómo hacerlo paso a paso**.
Esto tiene varias ventajas:

* El código es más legible y cercano a la lógica de la aplicación.
* React se encarga de las actualizaciones del DOM de forma óptima.
* Evita errores comunes al manipular el DOM manualmente con métodos como `document.createElement()` o `appendChild()`.



---

##  Posibles mejoras con nuevos componentes

Para mejorar la app sin romper su coherencia visual ni lógica, se podrían añadir:

1. **`ComponenteClima`** – Muestra el clima actual y cómo influye en las huertas.
2. **`ComponenteConsejos`** – Lista de recomendaciones ecológicas y sostenibles.
3. **`ComponenteTuHuerta`** – Una Sección donde den tips para montar tu huerta y como cuidarla .


