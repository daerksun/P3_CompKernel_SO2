# P3_CompKernel_SO2

## 1. **¿Cómo hacer un respaldo de una máquina virtual? y ¿cómo levantar ese respaldo?**

Nos colocamos en el menu del archivo de virtualBox y seleccionamos exportar servicio virtualizado

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/1.png "Im1")

Damos el botón Next , para usar el modo guiado del sistema

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/2.png "Im1")

Seleccionamos la ruta donde queremos que se guarde nuestra copia, y pulsamos el botón next, una vez que se haya seleccionado la ruta

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/3.png "Im1")
![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/4.png "Im1")

Seleccionamos el botón de exportar , y esperemos que se exporte de manera completa el archivo

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/5.png "Im1")

Se habrá creado con éxito el respaldo en la ruta que nosotros seleccionamos

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/6.png "Im1")

Para importar nos dirigimos al menú de los archivos en virtual Box y seleccionamos importar servicio virtualizado

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/7.png "Im1")

Indicamos la ruta donde tenemos guardado nuestro respaldo y damos el botón next

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/8.png "Im1")

Nos generara las opciones que queremos para nuestra maquina virtual , en este caso nosotros no le modificaremos nada y le damos al botón next

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/9.png "Im1")
![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/10.png "Im1")

Se habrá generado con exito nuestra maquina virtual

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/11.png "Im1")



## 2. **Explicar la nomenclatura del kernel.**

Se podría conocer al kernel , como el corazón de cualquier sistema operativo , ya que este en su mayor parte es quien se encarga tanto del software y el hardware de un sistema y puedan interactuar de la mejor forma posible entre estos.
En linux , a partir de la versión 2.6 se establecieron ciertos cambios en la nomenclatura , para un manejo más sencillo de esta que se caracteriza por la siguiente AA.BB.CC.DD  donde:

	AA. Nos indica la versión del Kernel
	BB. Nos indica la revisión actual del Kernel
	CC. Nos proporciona información sobre si el núcleo cuenta con revisiones menores, como los son los drivers.
	DD. Nos indica los arreglos de fallos en el kernel y sus actualizaciones

## 3. **Enlistar paquetes requeridos para la compilación y ¿cómo instalarlos desde terminal?**

Segun el manual consultado, para que sea exitosa la compilacion del kernel se requiere instalar tres paquetes, **build-essential, libncurse5-dev fakeroot**, con la instrucción **sudo apt-get install**.

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/12.png "Im1")


## 4. **¿Cómo descargar una versión de kernel desde terminal?.**

wget "https://cdn.kernel.org/pub/linux/kernel/v5.x/linux-5.9.tar.xz"

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/13.png "Im1")

Otra forma es usando la instrucción **sudo install** para instalar un paquete llamado **linux-source-version**, que en este caso se usa la version 5.9, y se descargará en la direccion /usr/src

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/14.png "Im1")
![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/15.png "Im1")


## 5. **¿Cómo extraer el código comprimido del kernel desde terminal?**

tar avxf linux-5.9.tar.xz

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/16.png "Im1")

## 6. **¿Cómo configurar el kernel?**

El comando sysctl permite la visualización de los parámetros del kernel , además de también configurar los parámetros del kernel .

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/17.png "Im1")

## 7. **¿Cómo compilar el código del kernel?**

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/18.png "Im1")

## 8. **¿Cómo instalar módulos?**

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/19.png "Im1")

## 9. **¿Cómo instalar el kernel?**

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/20.png "Im1")

## 10. **¿Cómo indicarle a la computadora con cuál kernel debe iniciar?**

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/21.png "Im1")

## 11. **¿Cómo verificar el cambio de kernel a partir de consola?**

![alt text](https://github.com/daerksun/P3_CompKernel_SO2/blob/main/Im/22.png "Im1")

