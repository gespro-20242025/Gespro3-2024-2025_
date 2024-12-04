Nombre de los miembros del equipo:
Marcos Zamorano Lasso
Alba Abril Luengo
María Molina Goyena
## Guía de cómo se realiza toda la secuencia de acciones desde que nos posicionamos en un nuevo commit del repositorio Go Bees hasta que pasa a estar visible en nuestra rama master local. 
La guía la vamos a llevar a cabo con una rama nueva llamada add cd cover 173 ii que se empleará para poder realizar las capturas de pantalla del proceso correctamente.
Destacar también que como la compañera Alba Abril Luengo no pudo realizar el clone del repositorio de clone bees correctamente al principio, en las capturas de gitkraken sólo saldrán María y Marcos, por lo que Alba ha sido la encargada de hacer este último commit.
Por otro lado, sí que se verá reflejado en las pull requests de git hub que fuimos alternando entre participantes para llevarlas a cabo, como se solicitaba en el enunciado de la práctica.
### 1)	Go Bees (GK): Posicionarse en el commit para subir cambios
 ![image](https://github.com/user-attachments/assets/891bda0e-3976-47a7-b5d7-69a3c2d83dd6)

  En el git hub de go bees buscamos el commit que vamos a actualizar.
  
 ![image](https://github.com/user-attachments/assets/e55ba5d1-e918-445e-be23-81213ee17400)

  Hacemos click derecho en el commit, y nos vamos a reset master to this commit. Vamos a hacer un reseteo 'Hard', para eliminar todos los cambios posteriores.

### 2)	P3(GK): Tener MASTER al día y estar posicionado en MASTER
 ![image](https://github.com/user-attachments/assets/07b237ee-22a1-4ac8-b0a4-635032bd2feb)

  Nos posicionamos en la rama master.
  Estando ahí nos dirigimos a P3 de forma local.
 ![image](https://github.com/user-attachments/assets/b08167b8-ab8a-4ad7-bfcf-a3b57463776c)

  Hacemos pull para bajar los cambios guardados para evitar conflictos, y después pulsamos a fetch all para descargar todos los cambios y estar al día con el proyecto.
### 3)	P3(GH):Crear rama a partir de tarea con nombre = a GO BEES
 ![image](https://github.com/user-attachments/assets/82c3b628-d8c3-4771-a573-8abd2d407b41)
 
 En el fork creado en github del proyecto de go bees creamos una rama a partir de la tarea con nombre que había en el go bees, en este caso, es add cd cover 173.
 (Hubo un problema con esta nueva issue creada y consultamos al profesor que creó otra issue igual, pero que sería la número 19 llamada add cd cover 173 ii, que es con la que se trabajará más   adelante. Lamento que esta captura esté desactualizada, ya que creamos la branch de la 19 en el momento y no se pudo realizar captura para esta. Por lo que la 18 que se muestra aquí es una issue desactualizada.)
 Tras esto, dejamos la configuración por defecto de checkout locally y pulsamos en el botón verde de abajo a la derecha que nos indica create branch.
 Con esto, ya podríamos ver la rama creada en el gitKraken.

### 4)	P3(GK): Posicionarse en rama local

 ![image](https://github.com/user-attachments/assets/8ea429e1-ba32-4fea-b015-d7ea845222c8)

 Para ello, primero nos habrá salido en el apartado de remote, del gitkraken, pero con pulsar dos veces sobre esta, nos la trasladará a local.

 ![image](https://github.com/user-attachments/assets/69ed3e0b-62f0-41c3-849e-d677188d7f09)
  
 Nos posicionamos entonces en la rama que acabamos de crear en local.
 
### 5)	Añadir cambios de carpeta GO BEES a la carpeta P3 (Excluyendo .git)

 ![image](https://github.com/user-attachments/assets/f175cbc8-e115-4af5-9c54-8a3d9b3e7f09)
 
  Nos metemos a la carpeta donde tenemos el repositorio de gobees y copiamos todo menos el .git
  
 ![image](https://github.com/user-attachments/assets/c0e93ce3-a93a-4d04-a00d-5cbba9f71c5f)

 Después, lo pegamos en la carpeta con nuestro fork del repositorio, sobreescribiendo los archivos correspondientes.

### 6)	Git Stage all + git commit (Nombre commit). Si Git Fetch All tiene cambios git pull + git push, si no solo git push.

Nos saldrá ahora un mensaje en gitKraken de 57 changes in directory, así que clicamos en el botón de view changes que aparece a la derecha de este mensaje emergente y nos aparecerá algo como lo siguiente:

 ![image](https://github.com/user-attachments/assets/177353c0-4f01-420b-a499-00c80d3fff99)
 
 Ahora, clicamos en stage all changes y nos saldrá lo siguiente:
 
 ![image](https://github.com/user-attachments/assets/b1e889bb-96d4-4f9f-be54-c6e14985888c)

 Se habrán movido todos los cambios de unstaged changes a staged changes para poder confirmarlos posteriormente.
 Posteriormente, le damos el nombre de la tarea a este commit, para detallar que estos son los cambios referentes a esta tarea:
 
  ![image](https://github.com/user-attachments/assets/6b3dca49-624f-4a54-84cb-5faa9b4b5485)

  Se habrán añadido los cambios a la rama:

  ![image](https://github.com/user-attachments/assets/b4bc8cbf-60cb-47ae-a529-1fffae98db7e)
  
  Antes de hacer push y que se les muestren los cambios a los demás miembros del equipo, primero hacemos un Fetch All y, si hay cambios nuevos,
  realizamos un pull para cargar estos nuevos cambios.
  Ahora hacemos push de los cambios antes de hacer pull request.
  Nos saldrá abajo un mensaje de verificación del push.
  
### 7)	Crear PRQ( de nombre proyecto A nuestro proyecto) MASTER

En github, vamos a nuestro fork y, en la barra de arriba, pulsamos en pull requests.

 ![image](https://github.com/user-attachments/assets/c5476312-6159-40cc-949d-a3ce31d2d2c2)
 
  Hacemos una nueva pull request clicando en new pull request.
  
 ![image](https://github.com/user-attachments/assets/d1000a98-a22a-4fbd-b7ab-ed1f28f596e2)
 
  Seleccionamos la pull request 19-add-cd-cover-173-ii que se nos muestra en esta ventana.
  
 ![image](https://github.com/user-attachments/assets/b0097814-1f2b-45fe-be14-7e9e61cd02ed)

 Pulsamos en create pull request.
 (El mensaje que sale en rojo era porque justo a la hora de hacer la pull request se hicieron cambios sobre este documento readme, pero fueron solucionados más adelante sin mucho problema para evitar conflictos.)

### 8)	Merge PRQ y actualizar MASTER en local

![image](https://github.com/user-attachments/assets/8300f9b7-d956-4da6-8761-2874e5f6662c)

  Pulsamos en create pull request.
  
 ![image](https://github.com/user-attachments/assets/0c5b7827-ca98-4103-87bd-304ae3e5b998)

 Vemos que no hay conflictos y pulsamos en merge branch.
 
![image](https://github.com/user-attachments/assets/2ae77bf4-b2da-43f2-a1da-367ea823e0f3)

Confirmamos el merge.

![image](https://github.com/user-attachments/assets/fa30fcfc-a00d-4bcf-a914-12f23defd8d8)

Nos sale un mensaje de confirmación de que el pull request se ha llevado a cabo de manera exitosa y se ha sincronizado con la rama master.
Acabamos haciendo un pull de la rama master:
![Captura de pantalla 2024-12-02 101234](https://github.com/user-attachments/assets/854497ed-31ef-49d8-98fb-2c4a4482f4d4)
![Captura de pantalla 2024-12-02 101253](https://github.com/user-attachments/assets/12ac7cf4-f226-4ba6-a5b2-f27eef3dca2c)

Podemos comprobar que el proceso ha sido exitoso.


(A partir de ahora se mostrará el resultado del proyecto para los 8 commits originales, no se incluirá el noveno empleado para la explicación de arriba, más que en una foto de github donde se indicará con un mensaje de este estilo).
## Git Kraken:
### Gráfico obtenido con una captura de pantalla con la lista de commits del repositorio:
![image](https://github.com/user-attachments/assets/ebc43272-8fd5-4565-9f83-4678df95d297)
Esta imagen muestra nuestro repositorio llamado Gespro3-2024-2025, en el que se visualizan varias ramas locales y remotas, incluyendo master y otras como 7-convert-annex-c-to-latex-151.

### Captura de pantalla del primer commit:
![image](https://github.com/user-attachments/assets/01ac3293-edee-4532-81b8-91211b1a7a42)
Aqui podemos visualizar un acaptura de pantalla del primer commit realizado, identificado como 1e1999, fue realizado por Marcurio222 el 25/11/2024 a las 9:58 con el título "Add cd Cover 173". Este commit modifica un total de 74 archivos y añade 388 líneas de código.

### Captura de pantalla del último commit:
![image](https://github.com/user-attachments/assets/99049420-5038-47b7-a46a-2b8b8fc44356)
También observamos el ultimo commit, identificado como e35948, titulado "Convert annex A to latex 179", fue realizado por Marcurio222 el 25/11/2024 a las 20:10 y afecta 6 archivos. 

 
## Github:
### La información del proyecto de Github obtenida desde la opción de menú "Insights→Pulse":

![image](https://github.com/user-attachments/assets/d107f4bc-9e94-4802-a846-e67160742ca8)
Para acceder a esta imagen, he ido en la barra de arriba a insights y a pulse en la barra lateral de la izquierda cuando entras en insights.
(Esta imagen en concreto incluye el commit que hicimos para las capturas de la primera parte del readme, por eso no quedan 8, sino 9).

### La información del proyecto de Github obtenida desde la opción menú "Insights→ Code frequency":

![image](https://github.com/user-attachments/assets/128420fe-2ad9-4fc6-9ce5-0b17246176fa)
Para acceder a esta imagen, he ido en la barra de arriba a insights y a code frequency en la barra lateral de la izquierda cuando entras en insights.

### Captura con la relación de las PRQs realizadas cerradas:
![image](https://github.com/user-attachments/assets/09a4704c-c06a-428b-969d-0edae26c82ac)

Para acceder a ella, he ido a pull requests y a closed.
Vemos que hemos seguido el orden de los commits de go bees, por lo que, la primera en cerrarse fue Add cd cover 173 y la última, convert annex A to latex 179.
El orden de Pull requests ha ido alternativamente como se solicita en el enunciado, ya que ha sido Marcos, María, Alba, sucesivamente, uno detrás de otro, finalizando con el último pull request llevado a cabo por María.
  

