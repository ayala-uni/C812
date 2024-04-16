# C812
Curso Maestría UNI Estructuras - C812

# Instalar Fenics en Windows con Virtual Box - Método 1

1. Installar Virtual Box 
https://www.virtualbox.org/wiki/Downloads
2. Crear su ambiente de Linux
- https://www.youtube.com/watch?v=ZrHVHyIt-PY 
- https://www.youtube.com/watch?v=e3g5wpK70Uw


3. Una vez tenga Linux/Ubuntu, vaya a su terminal y tipee lo siguiente:

~~~
sudo add-apt-repository ppa:fenics-packages/fenics
~~~

~~~
sudo apt update
sudo apt upgrade
sudo apt-get install fenics
sudo apt --fix-broken install   
~~~

4. Pruebe:
~~~
cd Fenics/
python3 poisson_fenics.py
~~~
# Instalar FreeFem en Windows con Anaconda - Método 2

1. Ver el tutorial:

https://youtu.be/wFh5gPv_R2c

# Instalar FreeFem en Windows

1. Descargar el ejecutable y seguir los pasos de instalación
https://www.ljll.math.upmc.fr/lehyaric/ffcs/install.htm

# Install Gmsh Windows
1. Descargar el ejecutable de la página siguiente, seleccionando la opción Windows
https://gmsh.info/

# Install Paraview Windows
1. Descargar el ejecutable de la página siguiente, seleccionando la opción Windows
https://www.paraview.org/download/


# Trabajando con mallas en Fenics y Freefem

1. Ejemplo de un dique en Gmsh:
~~~
https://www.pygimli.org/_examples_auto/1_meshing/plot_cad_tutorial.html
~~~