**PRÁCTICA 1**
	
**1º** `docker pull ubuntu`: comando para crear un copia.
   docker images: Para comprobar las imagenes creadas.
   
**2º** `docker run -d ubuntu`: para crear un contenedor sin nombre.
`docker ps -a`: para ver si el contenedor se ha creado (si se creado). No queda arrancado.
   docker le ha asignado un nombre random en mi caso objective_swartz
   
**3º** `docker -run -it --name u1 ubuntu`: para crear el contenedor con el nombre u1 y entrar directamente en el.
   
**4º** utilizamos `apt install -y iputils-ping`: para poder hacer ping necesitamos instalar esto en la máquina. Si puede hacer ping a google.com.

**5º** `docker -run  -it --name bono ubuntu`: para crear el contenedor bono.
   En el contenedor bono utilizamos `hostname -I` para conseguir su IP y en el anterior contenedor donde tenemos instalado utils-ping utilizamos el comando `ping 172.16.0.7` y si, tienen contacto.

**6º** Si cerramos las consolas los contenedores pasan al estado Exited ya que son de un solo uso.

**7º** `docker system df`: para ver el espacio ocupado.

**8º** `docker stats` para ver el uso en RAM utilizado por los contenedores.

**9º** `git clone https://github.com/cnovoaarias2001/Practica1.git: para clonar el repositorio`.

**10º** `git add readme2.md`: para añadir el archivo.

**11º** `git commit -m "Añadiendo readme2.md"`: para subir el archivo.

**12º** `git fetch`: para ver las diferencias entre repositorios. 
