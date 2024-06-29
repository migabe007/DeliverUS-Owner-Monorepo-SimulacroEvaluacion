# IISSI2-IS: Simulacro de examen de laboratorio

## Preparación del entorno

Windows:

* Abra un terminal y ejecute el comando `npm run install:all:win`.

Linux/MacOS:

* Abra un terminal y ejecute el comando `npm run install:all:bash`.

## Ejecución y depuración

* Para **ejecutar el backend**, abra un terminal y ejecute el comando `npm run start:backend`.

* Para **ejecutar el frontend**, abra un nuevo terminal y ejecute el comando `npm run start:frontend`.

* Para **depurar el backend**, asegúrese de que **NO** existe una instancia en ejecución, pulse en el botón `Run and Debug` de la barra lateral, seleccione `Debug Backend` en la lista desplegable, y pulse el botón de *Play*.

* Para **depurar el frontend**, asegúrese de que **EXISTE** una instancia en ejecución, pulse en el botón `Run and Debug` de la barra lateral, seleccione `Debug Frontend` en la lista desplegable, y pulse el botón de *Play*.

---

## Enunciado

Evaluación individual laboratorio. Junio 2022.

Nutrientes saludables

Una vez se ha puesto en marcha la primera versión de DeliverUS, los inversores han solicitado la inclusión de una nueva funcionalidad que consiste en informar al cliente de los gramos de macronutrientes que contienen cada uno
de los productos. Tras la reunión con el cliente, se ha establecido los siguientes requisitos:

1.- Debido a la normativa reguladora de alimentación, se pide que se informe al cliente de la cantidad de carbohidratos, proteínas y grasas por cada 100 gramos de cada uno de los productos que están a la venta en DeliverUS.

2.- Dada la existencia de platos hipercalóricos que no están recomendados en una dieta saludable se pide que un plato no pueda contener más de 1000 calorías por 100g de producto. Para ello, sevusará la siguiente formula aproximada de cálculo energético
Calorías producto = (grasas * 9) + (proteínas * 4) + (carbohidratos * 4)

Se pide que:
1.- Implemente los cambios que sean necesarios en el backend.
2.- Implemente validación de servidor y cliente con los requisitos de calorías máximas.
3.- Muestre los datos de calorías por 100g, carbohidratos, proteínas y grasas en cada uno de los productos que se muestran en la pantalla RestaurantDetailScreen.

• Nota: No es necesario modificar los seeders. Recuerde que los valores numéricos enviados por el frontend, llegan al backend como string cuando se usan TextInputs en el componente InputItem. No olvide realizar un casting a float de dichos valores para que el backend los trate sin problema.

Lugar de entrega: Enseñanza Virtual

Procedimiento para la entrega:
1. Elimine las carpetas node_modules de los proyectos de backend y frontend y la carpeta .expo del proyecto frontend.
2. Cree un zip que incluya ambos proyectos.
3. Avise a su profesor antes de realizar el envío.
4. Cuando tenga el visto bueno de su profesor, envíe el fichero resultante a través de enseñanza virtual.
5. Una vez enviado, elimine los proyectos al completo.

### Ejercicio 1

Realice todos los cambios necesarios en el proyecto de backend para implementar el nuevo requisito.

### Ejercicio 2

Realice todos los cambios necesarios en el proyecto de frontend para implementar el nuevo requisito.


![captura1](https://user-images.githubusercontent.com/19324988/235651836-d57d9c7e-4b8d-46a2-9154-b414a7abf702.png)


![captura2](https://user-images.githubusercontent.com/19324988/235651849-4d03c7d9-f332-4952-8cbc-9fa5db4f97fb.png)


![captura3](https://user-images.githubusercontent.com/19324988/235651853-e1d13916-4f47-4e17-97e0-5696b647bee7.png)
