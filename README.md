# GymAndEat
Aplicación final de curso

Esta App desarrollada en IONIC será una continuación de la App que desarrollé en el primer trimestre.

En la primera versión, no teníamos ni gestión de usuarios(registro,login,bbdd) y los alimentos se añadían a través de un json que cree yo mismo, por lo tanto era una aplicación bastante limitada.

Para esta nueva versión, además de crear una bbdd en firebase y tener gestión de usuarios, quiero que los alimentos sean proporcionados por una API externa, a así tener una mayor variedad de alimentos, y quiero hacer otro apartado donde se puedan gestionar las rutinas del gym para cada usuario.

En resumen, la aplicación consta de 2 partes:
-- Una parte de alimentación, donde tendremos alimentos con su información nutricional que se añadirán a través de una Api externa, y si el usuario quiere añadir uno nuevo puede hacerlo a través del Capacitor, almacenándolo localmente.

-- Una parte de gym, donde el usuario guardará sus rutinas de gym y su progreso en una bbdd como Firebase, por lo tanto si entramos en al app con otro usuario, se verá el progreso del usuario logueado.
