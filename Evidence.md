Conexión ssh Linux a Linux

1\. Verificamos que el comando ssh este corriendo en nuestro sistema
Linux:

![](Pictures/100000010000032A00000065CBBC6153.png){width="6.9252in"
height="0.8634in"}

systemctl status ssh: Chequea el estado actual de ssh service en nuestra
máquina

2\. Verificar la ip de la computadora co el comando ip a

![](Pictures/100000010000032A000000655B1B5E5C.png){width="6.9252in"
height="0.8634in"}

ip: internet protocol

a: address

Este comando muestra las interfaces de red y sus direcciones ip.

3\. Realizamos la conexión:

![](Pictures/10000001000002C40000018B13CEFFEB.png){width="6.9252in"
height="3.8634in"}

Haciendo uso del comando ssh nombredeusuario@dirección ip nos conectamos
a la otra computadora.

4\. Creamos un directorio desde nuestra máquina a la máquina a la cual
nos conectamos.

![](Pictures/10000001000002C4000000F7DEDC2906.png){width="6.9252in"
height="2.4154in"}

5\. Una vez dentro del directorio, creamos un archivo .txt

![](Pictures/10000001000002C40000005A892753A6.png){width="6.9252in"
height="0.8799in"}

6\. Lo abrimos haciendo uso del editor nano

![](Pictures/10000001000002F4000000356340DD0B.png){width="6.9252in"
height="0.4854in"}

![](Pictures/10000001000003DC0000023F83FDACA2.png){width="6.9252in"
height="4.0299in"}

7\. Verificamos los permisos del los archivos:

![](Pictures/10000001000002F400000078AC346195.png){width="6.9252in"
height="1.0984in"}\
Podemos ver que el usuario tiene permiso de lectura y escritura.

8\. Cambiamos permisos

![](Pictures/10000001000003D00000016DDB46C896.png){width="6.9252in"
height="2.5898in"}\
