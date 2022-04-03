# GymAndEat
Aplicación final de curso

![gymandeat](https://user-images.githubusercontent.com/72436145/161440435-8c374d76-7400-4b3d-9d23-33f1beade971.png)

Esta App desarrollada en IONIC será una continuación de la App que desarrollé en el primer trimestre.

En la primera versión, no teníamos ni gestión de usuarios(registro,login,bbdd) y los alimentos se añadían a través de un json que cree yo mismo, por lo tanto era una aplicación bastante limitada.

Para esta nueva versión, además de crear una bbdd en firebase y tener gestión de usuarios, quiero que los alimentos sean proporcionados por una API externa, a así tener una mayor variedad de alimentos, y quiero hacer otro apartado donde se puedan gestionar las rutinas del gym para cada usuario.

En resumen, la aplicación consta de 2 partes:
-- Una parte de alimentación, donde tendremos alimentos con su información nutricional que se añadirán a través de una Api externa, y si el usuario quiere añadir uno nuevo puede hacerlo a través del Capacitor, almacenándolo localmente.

![userIonic](https://user-images.githubusercontent.com/72436145/161440443-fce49c6d-0878-443f-a4f6-7f8a4b30f42e.png)
![favIonic](https://user-images.githubusercontent.com/72436145/161440448-4a3d56be-1e34-4d1b-9ea4-23507b1d0356.png)
![alimentosIonic](https://user-images.githubusercontent.com/72436145/161440450-ab25c8af-298d-4d64-b7af-411a0ec555e4.png)


-- Una parte de gym, donde el usuario guardará sus rutinas de gym y su progreso en una bbdd como Firebase, por lo tanto si entramos en al app con otro usuario, se verá el progreso del usuario logueado.
