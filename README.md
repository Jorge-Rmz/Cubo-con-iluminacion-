# Cubo-con-iluminacion

# Cubo con Iluminación

#### Como podemos ver en la siguiente imagen podemos observa la importación de todas las librerías a utilizar, también se puede observar el método main el  cual tiene las dimensiones de la ventana entre otros objetos  que nos servirán para poder mostrar nuestra figura.
![fIGURA 15](https://user-images.githubusercontent.com/71052252/143891481-84dd172c-0797-4c22-a635-8b3e640499d9.png)

#### El siguiente código que se puede observar es lo que hará el programa una vez que se le presione cerrar, con la línea animator.stop se detendrá la animación y el siguiente código se cerrará la ventana. Y las siguientes líneas nos sirve para centrar la ventana y hacerla visible. 
![fIGURA 16](https://user-images.githubusercontent.com/71052252/143891483-0ab314db-b6ae-4f52-9404-63532668fe7a.png)

#### En el método init se inicializa la variable gl que nos servirá para dibujar las figuras, y también asignamos las coordenadas en donde se podrá dibujar las figuras.
![fIGURA 17](https://user-images.githubusercontent.com/71052252/143891484-a981edfe-7c7a-451d-a27c-fea51eb49bbc.png)

#### En la función reshape se pasa cuatro parámetros de tipo int, en el interior de la función se determinan el tamaño que tendrá la ventana donde se mostrara las figuras, se inicializa la matriz actual con los valores de la matriz identidad de orden 4*4, también observamos las líneas de código para que podamos ver la figura a una vista simétrica  este valor se multiplica por la matriz actual.
![fIGURA 18](https://user-images.githubusercontent.com/71052252/143891487-1495bd92-67a2-4e9b-8c6b-5f8764e5936e.png)

#### En el método display tenemos el siguiente código, primero se limpie todo  el área en donde se dibujara la figura, después se habilita la iluminación y también se habilita la luz individualmente, después se declaran las matrices de los diferentes luces que tendrá nuestro cubo para tener el acabado de iluminación, se declara la matriz para la luz ambiente, luz difusa, posición de la luz y la dirección de la luz, después aplicamos la luz difusa y la posición que tendrá esa luz a nuestra figura, y por ultimo se define los materiales que tendrá nuestro cubo.

![fIGURA 19](https://user-images.githubusercontent.com/71052252/143891489-8ebfd22d-1f1a-47ce-af39-8fd6c043fcb6.png)

#### Ahora vemos el código el cual nos servirá para dibujar cada uno de los lados de nuestra figura 3D aquí se muestra el código para dibujar tres de los lados, y en todos los lados a dibujar se hace lo mismo primero se pone un color al lado que bajos a dibujar, después se dibuja los vértices de la figura que formara una parte de nuestra figura 3D, y así proseguimos con los siguientes lados.
![fIGURA 20](https://user-images.githubusercontent.com/71052252/143891490-a4493d76-11aa-48ab-a3a3-fca6fcd23138.png)

#### Aquí vemos las dos ultimas caras de nuestra figura 3D, que se realiza lo mismo que las caras anteriores primero se le asigna un color y después se posicionan cada uno de los vértices y por ultimo se dibuja dicha figura, y así hasta completar todos los lados.
![fIGURA 21](https://user-images.githubusercontent.com/71052252/143891491-d479e3b3-96f5-4a07-83dc-83c31a6f28fb.png)

# Resultados
![fIGURA 22](https://user-images.githubusercontent.com/71052252/143891493-374a5b80-95cf-488e-9949-4641914a4d91.png)
