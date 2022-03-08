# Contribuir a repositorio existente

 - Clonamos la tarea mediante un git clone y el link.
 - Nos situamos en el repositorio creado mediante cd.

<img src="Img/Foto5.png" />
<br>

 - Creamo una rama llamada my-branch mediante git branch y el nombre de la rama.
 - Nos situamos en ella mediante git checkout y el nombre.
<img src="Img/Foto6.png" />
<br>

 - Creamos 2 archivos mediante touch, los llamaremos file1.md y file2.md
 - Los subimos mediante git add y los nombres.
 - 
<img src="Img/Foto7.png" />
<br>

 - Hacemos un git commit -m y los archivos para actualizar los cambios.

<img src="Img/Foto8.png" />
<br>

 - Hacemos un git push origin my-branch para subir los cambios. 

# Crear repositorio y subirlo a git

  - Creamos un repositorio megiante git init my-repo.
  - Nos situamos en el mediante cd

<img src="Img/Foto1.png" />
<br>

 - Creamos un archivo README.md mediante el comando touch.
 - Lo añadimos mediante un git add.

<img src="Img/Foto2.png" />
<br>

 - Hacemos un git commit -m "comentario" README.md para actualizar los cambios.

<img src="Img/Foto3.png" />
<br>

 - Usasmos git remote add origin https://github.com/JoanRiudalaDodero/my-repo.git para añadir el repositorio a github.

<img src="Img/Foto4.png" />
<br>

 - Usamos git push --set-upstream origin "la rama" para actualizar la rama.

# Contribuir a rama existente

 - Nos situamos en el repositorio en el que deseamos trabajar mediante cd y el nombre del repositorio.
 - Y hacemos un git pull para asegurarnos que el repositorio tiene todo lo que debe tener, le pueden faltar cosas ya que un compañero puede haber subido o editado cosas remotamente.

<img src="Img/Foto9.png" />
<br>

 - Mediante git checkout readme-edits nos cambiariamos a dicha rama.

<img src="Img/Foto10.png" />
<br>

 - Usamos nano para entrar en un archivo existente, dentro del archivo usamos ctrl+o para guardar y ctrl+x para salir.
 - Git add para indicar que se ha cambiado y se va a subir.

<img src="Img/Foto11.png" />
<br>

 - Usamos git commit -m README.md para afirmar los cambios.
 - Git push para subir la rama y tener los cambios actualizados a la pagina de github.

<img src="Img/Foto12.png" />
