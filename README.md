# P3_CompKernel_SO2

1. ¿Cómo hacer un respaldo de una máquina virtual? y ¿cómo levantar ese respaldo?
Nos colocamos en el menu del archivo de virtualBox y seleccionamos exportar servicio virtualizado

Damos el botón Next , para usar el modo guiado del sistema


 ![alt text](https://github.com/daerksun/Practica1.ManejodeDiscos/blob/main/Imagenes/22.png "Im22")




Seleccionamos la ruta donde queremos que se guarde nuestra copia , y seleccionamos el botón next , una vez que se haya seleccionado la ruta


Seleccionamos el botón de exportar , y esperemos que se exporte de manera completa el archivo


Se habrá creado con éxito el respaldo en la ruta que nosotros seleccionamos


Para importar nos dirigimos al menú de los archivos en virtual Box y seleccionamos importar servicio virtualizado

Indicamos la ruta donde tenemos guardado nuestro respaldo y damos el botón next


Nos generara las opciones que queremos para nuestra maquina virtual , en este caso nosotros no le modificaremos nada y le damos al botón next


Se habrá generado con exito nuestra maquina virtual




2. Explicar la nomenclatura del kernel.
Se podría conocer al kernel , como el corazón de cualquier sistema operativo , ya que este en su mayor parte es quien se encarga tanto del software y el hardware de un sistema y puedan interactuar de la mejor forma posible entre estos .
En linux , a partir de la versión 2.6 se establecieron ciertos cambios en la nomenclatura , para un manejo más sencillo de esta que se caracteriza por la siguiente AA.BB.CC.DD  donde :
    AA. Nos indica la versión del Kernel
    BB. Nos indica la revisión actual del Kernel
    CC. Nos proporciona información sobre si el núcleo cuenta con revisiones menores,      como los son los drivers .
    DD. Nos indica los arreglos de fallos en el kernel y sus actualizaciones
##**3. Enlistar paquetes requerido para la compilación y ¿cómo instalarlos desde terminal?**

Segun el manual consultado, para que sea exitosa la compilacion del kernel se requiere instalar tres paquetes, **build-essential, libncurse5-dev fakeroot**, con la instrucción **sudo apt-get install**.

![alt text](https://github.com/daerksun/P3_CompKernel_SO2.git/tree/main/Im/3.png "Im1")


4. ¿Cómo descargar una versión de kernel desde terminal?.
wget "https://cdn.kernel.org/pub/linux/kernel/v5.x/linux-5.9.tar.xz"


5. ¿Cómo extraer el código comprimido del kernel desde terminal?
tar avxf linux-5.9.tar.xz

6. ¿Cómo configurar el kernel?
El comando sysctl permite la visualización de los parámetros del kernel , además de también configurar los parámetros del kernel .

7. ¿Cómo compilar el código del kernel?

8. ¿Cómo instalar módulos?




9. ¿Cómo instalar el kernel?

10. ¿Cómo indicarle a la computadora con cuál kernel debe iniciar?
/*DUDA*/

11. ¿Cómo verificar el cambio de kernel a partir de consola?

