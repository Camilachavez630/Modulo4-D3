# Modulo4-D3
El prototipo debe implementarse mediante una aplicación de consola en Python, la cual incluirá un script principal que gestionará la ejecución del juego,
y una clase dedicada a la creación de personajes, que deberá ser importada en el script principal. Las decisiones del usuario en el juego,
así como el nombre de su personaje, se obtendrán a través de entradas por teclado (input).

La clase para la creación de personajes debe cumplir con los siguientes requisitos:

Cada personaje tendrá un nombre, que se debe especificar al momento de su creación. Al iniciar, cada personaje tendrá nivel 1 y 0 puntos de experiencia 
(estos son los únicos valores permitidos al momento de la creación). Será posible consultar o modificar el estado de un personaje. Al consultar su estado,
se debe mostrar su nombre, nivel y experiencia actual. Al asignar un nuevo valor de estado, este valor representará la cantidad de experiencia obtenida por el personaje. 
Según la experiencia otorgada, se deberá actualizar tanto su nivel como su experiencia siguiendo estas reglas: La experiencia debe estar en el rango de 0 a 99 inclusive.
El nivel mínimo será 1, sin un límite máximo. Por cada 100 puntos de experiencia acumulados, el personaje sube un nivel (es decir, su nivel aumenta en 1). 
Ejemplo: Si el personaje está en nivel 1 con 0 puntos de experiencia, y se le asignan 250 puntos, subirá al nivel 3 con 50 puntos de experiencia restantes. 
Si la experiencia asignada es negativa, se restará de la experiencia actual del personaje. Si la experiencia resulta ser menor que 0, el personaje bajará un nivel 
(su nivel disminuirá en 1). Ejemplo: Un personaje con nivel 3 y 50 puntos de experiencia que reciba -150 puntos quedará en nivel 2 con 0 puntos de experiencia. 
Si el personaje ya está en nivel 1 y tiene 0 puntos de experiencia, no se modificará su nivel ni su experiencia al recibir valores negativos.






