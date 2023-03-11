# cow-proyect
idv: Un campo entero que representa un identificador único para la vaca.
weight: Un campo entero que representa el peso actual de la vaca. Permite valores nulos y en blanco.
birth_weight: Un campo entero que representa el peso al nacer de la vaca. Permite valores nulos y en blanco.
weaning_weight: Un campo entero que representa el peso de la vaca cuando fue destetada. No permite valores nulos ni en blanco.
pregnancy_status: Un campo de caracteres que representa el estado de embarazo de la vaca. Tiene una longitud máxima de 20 caracteres y tiene tres opciones posibles, que están definidas en la clase enum PregnancyStatus.
description: Un campo de texto que representa una descripción de la vaca.
created_at: Un campo de fecha y hora que representa la fecha y hora en que se creó la vaca. Se establece automáticamente cuando se crea un nuevo objeto vaca.
updated_at: Un campo de fecha y hora que representa la fecha y hora en que se actualizó por última vez la vaca. Se actualiza automáticamente cuando se guarda un objeto vaca.
father: Un campo uno a uno que representa el padre de la vaca. Permite valores nulos y en blanco. Está relacionado con el mismo modelo Cow.
mother: Un campo uno a uno que representa la madre de la vaca. Permite valores nulos y en blanco. Está relacionado con el mismo modelo Cow.
birth_date: Un campo de fecha que representa la fecha de nacimiento de la vaca. Permite valores nulos y en blanco.
