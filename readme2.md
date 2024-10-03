### 1. Descargar e comprobar que unha imaxe está no teu equipo

Creo unha imaxe de Ubuntu con Docker co comando: `docker run -it ubuntu`
Para comprobar que unha imaxe está no meu equivo escribo o comando: `docker image ls`
### 2. Crear un contenedor sen nome, queda arrincado?, cómo obtés o nome?
>[!NOTE]
>Non sei como facelo sen nome xa que Docker asignasello automaticamente.
>Podo ver o nome co comando: `docker ps`
### 3. Crea un contenedor coo nome 'u1', cómo accedes a el?
Creo un contenedor coa imaxe ubuntu e o nomeo 'u1' co seguinte comando: `docker run --name u1 -it ubuntu bash` 
e accedo a él con : `docker start u1`
### 4. Comproba a súa ip e fai ping a google.com
>[!TIP]
> Seguramente non tenias os comandos bash basicos coma min, polo que igual eu fixen, primero teras que insatalar os comandos: 
```
`**apt-get update && apt-get install -y iputils-ping**` para instalar o comando ping e 
`apt install iproute2` , para instalar o comando ip
```
>Despois fago ping a google.com co comando `ping google.com`. E sí, hace ping a Google.com

### 5. Crea un contenedor coo nome 'bono', pódes facer ping entre os contenedores?
Creo o contenedor bono: `docker run --name u1 -it ubuntu bash`

Primero para coñecer se fan ping, preciso saber as súas ip.
Nun contenedor, por exemplo o 'u1', fago `ip a` para saber a dirección ip; e noutro contenedor, 'bono',fago ping a esa direccion de u1.
### 6. Se pechas as terminales, qué pasa coo contenedor?
### 7. Cánta memoria no disco duro ocupaches? usa docker para calculalo
### 8. Cánta RAM ocupan os contenedores? Crea varios para calculalo
### 9. Cómo fixeches para clonar o repositorio
### 10. Cómo engades o arquivo readme2.md
### 11. Os pasos a seguir para subir o arquivo que estás editando e o arquivo readme2.md
### 12. Cómo comprobarías que existen diferencias entre o teu repositorio local e o remote.









Crea un contenedor coo nome 'bono', pódes facer ping entre os contenedores?
 Para iso, instalo o comando con 
Agora 