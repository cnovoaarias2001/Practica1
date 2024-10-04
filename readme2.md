https://github.com/cnovoaarias2001/Practica1.git

PRÁCTICA 1
	
1º docker pull ubuntu: comando para crear un copia.
   docker images: Para comprobar las imagenes creadas.
   
2º docker run -d ubuntu: para crear un contenedor sin nombre.
   docker ps -a: para ver si el contenedor se ha creado (si se creado). No queda arrancado.
   docker le ha asignado un nombre random en mi caso objective_swartz
   
3º docker -run -it --name u1 ubuntu: para crear el contenedor con el nombre u1 y entrar directamente en el.
   
4º utilizamos apt install -y iputils-ping: para poder hacer ping necesitamos instalar esto en la máquina. Si puede hacer ping a google.com.

5º docker -run  -it --name bono ubuntu: para crear el contenedor bono.
   En el contenedor bono utilizamos hostname -I para conseguir su IP y en el anterior contenedor donde tenemos instalado utils-ping utilizamos el comando ping 172.16.0.7 y si, tienen contacto.

6º Si cerramos las consolas los contenedores pasan al estado Exited ya que son de un solo uso.

7º docker system df: para ver el espacio ocupado.
TYPE            TOTAL     ACTIVE    SIZE      RECLAIMABLE
Images          4         4         304.4MB   0B (0%)
Containers      18        3         41.99MB   41.99MB (99%)
Local Volumes   0         0         0B        0B
Build Cache     0         0         0B        0B

8º docker stats para ver el uso en RAM utilizado por los contenedores.
CONTAINER ID   NAME                   CPU %     MEM USAGE / LIMIT     MEM %     NET I/O           BLOCK I/O        PIDS
fe8365909e73   nervous_pasteur        0.00%     6.684MiB / 4.625GiB   0.14%     16.2kB / 1.87kB   0B / 4.1kB       82
6fd032a5822f   goofy_nash             0.00%     6.891MiB / 4.625GiB   0.15%     22.8kB / 5.66kB   3.94MB / 4.1kB   82
226ddc0d7245   flamboyant_chebyshev   0.00%     1.254MiB / 4.625GiB   0.03%     29.7kB / 0B       893kB / 262kB    1

9º git clone https://github.com/cnovoaarias2001/Practica1.git: para clonar el repositorio.

10º git add readme2.md

11º git commit -m "Añadiendo readme2.md"

12º git fetch
