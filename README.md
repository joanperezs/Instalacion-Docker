# Instalación de Docker en Windows, Linux o Mac
### Hecho por Joan Pérez Susidko

## Primeros pasos

Para instalar Docker necesitaremos ir a la página https://docs.docker.com/get-docker/ y seleccionar nuestro sistema operativo, en este caso Windows.

![image](https://user-images.githubusercontent.com/101748401/173258790-aee5c754-4554-45de-9a35-9970b7ffa2a0.png)

Una vez seleccionado, procedemos a descargar el instalador dándole al botón `Docker Desktop for Windows`

Al abrir el instalador nos saldrá dos opciones, lo dejaremos activados y pasamos al siguiente paso.

![image](https://user-images.githubusercontent.com/101748401/173258947-2cc1446d-056a-4aba-8a5d-f607c8d3a397.png)

Al acabar la instalación nos pedirá reiniciar el ordenador.

Al reiniciar tendremos que aceptar las políticas de uso.

![image](https://user-images.githubusercontent.com/101748401/173259012-10ec3bbb-827f-4596-b0dd-9a9c88bfab38.png)

Una vez aceptadas nos saltará un aviso para instalar un paquete kernel de Linux. Para ello nos dirigiremos al enlace que nos ofrece docker.
![image](https://user-images.githubusercontent.com/101748401/173259040-f3a3f26c-d743-4379-b4d3-f24e27501e19.png)

Una vez dentro, lo instalaremos dandole al botón `Paquete de actualización del kernel de Linux en WSL 2 para máquinas x64`
![image](https://user-images.githubusercontent.com/101748401/173259161-e0298590-c865-42f2-bcf8-008db15f8726.png)

Una vez instalado le damos a restart y nos saldrá este tutorial. 

Simplemente procedemos a darle start.
![image](https://user-images.githubusercontent.com/101748401/173259239-3176899a-3fad-4e6f-9540-3e5ff0f77f64.png)

Ejecutamos un helloworld para comprobar el funcionamiento.
```
docker run hello-world
```
![image](https://user-images.githubusercontent.com/101748401/173259295-801e1aa8-c939-4bbb-b619-d4a9e7d8df0a.png)




