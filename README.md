Nombre de los miembros del equipo:
Marcos Zamorano Lasso
Alba Abril Luengo
María Molina Goyena
## Guía de cómo se realiza toda la secuencia de acciones desde que nos posicionamos en un nuevo commit del repositorio Go Bees hasta que pasa a estar visible en nuestra rama master local. 
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
 
 En el fork creado en github del proyecto de go bees creamos una rama a partir de la tarea con nombre = a GO BEES.

### 4)	P3(GK): Posicionarse en rama local
 ![image](https://github.com/user-attachments/assets/69ed3e0b-62f0-41c3-849e-d677188d7f09)
  Nos posicionamos en la rama que acabamos de crear en local
### 5)	Añadir cambios de carpeta GO BEES a la carpeta P3 (Excluyendo .git)
 ![image](https://github.com/user-attachments/assets/f175cbc8-e115-4af5-9c54-8a3d9b3e7f09)
  Nos metemos a la carpeta donde tenemos el repositorio de gobees y copiamos todo menos el .git
 ![image](https://github.com/user-attachments/assets/c0e93ce3-a93a-4d04-a00d-5cbba9f71c5f)

### 6)	Git Stage all + git commit (Nombre commit). Si Git Fetch All tiene cambios git pull + git push, si no solo git push.
 ![image](https://github.com/user-attachments/assets/177353c0-4f01-420b-a499-00c80d3fff99)
  Clicamos en stage all changes y nos saldrá lo siguiente:
 
 ![image](https://github.com/user-attachments/assets/b1e889bb-96d4-4f9f-be54-c6e14985888c)
  ![image](https://github.com/user-attachments/assets/6b3dca49-624f-4a54-84cb-5faa9b4b5485)
  ![image](https://github.com/user-attachments/assets/b4bc8cbf-60cb-47ae-a529-1fffae98db7e)

 
  Ahora hacemos push de los cambios antes de hacer pull request.
  Nos saldrá abajo un mensaje de verificación del push.
### 7)	Crear PRQ( de nombre proyecto A nuestro proyecto) MASTER
 ![image](https://github.com/user-attachments/assets/c5476312-6159-40cc-949d-a3ce31d2d2c2)
  Hacemos una nueva pull request clicando en new pull request.
 ![image](https://github.com/user-attachments/assets/d1000a98-a22a-4fbd-b7ab-ed1f28f596e2)
  Seleccionamos la pull request 19-add-cd-cover-173-ii.
 ![image](https://github.com/user-attachments/assets/b0097814-1f2b-45fe-be14-7e9e61cd02ed)

### 8)	Merge PRQ y actualizar MASTER en local

![image](https://github.com/user-attachments/assets/8300f9b7-d956-4da6-8761-2874e5f6662c)
  Pulsamos encreate pull request
 ![image](https://github.com/user-attachments/assets/0c5b7827-ca98-4103-87bd-304ae3e5b998)
![image](https://github.com/user-attachments/assets/2ae77bf4-b2da-43f2-a1da-367ea823e0f3)
![image](https://github.com/user-attachments/assets/fa30fcfc-a00d-4bcf-a914-12f23defd8d8)
  Acabamos haciendo un pull de la rama masters 
![Captura de pantalla 2024-12-02 101234](https://github.com/user-attachments/assets/854497ed-31ef-49d8-98fb-2c4a4482f4d4)
![Captura de pantalla 2024-12-02 101253](https://github.com/user-attachments/assets/12ac7cf4-f226-4ba6-a5b2-f27eef3dca2c)

## Git Kraken:
### Gráfico obtenido con una captura de pantalla con la lista de commits del repositorio:
![image](https://github.com/user-attachments/assets/ebc43272-8fd5-4565-9f83-4678df95d297)

### Captura de pantalla del primer commit:
![image](https://github.com/user-attachments/assets/01ac3293-edee-4532-81b8-91211b1a7a42)

### Captura de pantalla del último commit:
![image](https://github.com/user-attachments/assets/99049420-5038-47b7-a46a-2b8b8fc44356)


 
## Github:
### La información del proyecto de Github obtenida desde la opción de menú "Insights→Pulse":
### La información del proyecto de Github obtenida desde la opción menú "Insights→ Code frequency":
### Captura con la relación de las PRQs realizadas cerradas:
![image](https://github.com/user-attachments/assets/09a4704c-c06a-428b-969d-0edae26c82ac)

Vemos que hemos seguido el orden de los commits de go bees, por lo que, la primera en cerrarse fue Add cd cover 173 y la última, convert annex A to latex 179.
El orden de Pull requests ha ido alternativamente como se solicita en el enunciado, ya que ha sido Marcos, María, Alba, sucesivamente, uno detrás de otro, finalizando con el último pull request llevado a cabo por María.
  

