# practica-wifi-segura
## **Trabajo N°6 de Ciberseguridad**
Empezamos este trabajo entrando en la web "neverssl.com" y procedemos a ingresar al menu de desarollador (F12)
![](https://github.com/SEJ-notcye/practica-wifi-segura/blob/main/Screenshot1.png)
y rapidamente nos movemos a la seccion de network/red o en el caso de internet explorer el icono de "Wifi" 
![](https://github.com/SEJ-notcye/practica-wifi-segura/blob/main/Screenshot2.png)
para poder ver los datos que estamos buscando recargamos la pagina tocando el boton en pantalla  
![](https://github.com/SEJ-notcye/practica-wifi-segura/blob/main/Screenshot3.png)
luego de recargada la pagina aparecen los movimientos de red y 2 archivos, nos centramos en el primero llamado "online/" que es el que nos interesa y se despliega un menu con datos acerca de la web, en principio datos generales como la url y el metodo de solicitud entre otros
![](https://github.com/SEJ-notcye/practica-wifi-segura/blob/main/Screenshot4.png)
lo mas importante e interesante a destacar es que en este menu podemos ver los encabezados de respuesta de la web y los Request headers donde podemos observar datos a tener en cuenta como el protocolo de la web, su metodo GET e incluso datos del usuario.
<a name="ancla5"></a>![](https://github.com/SEJ-notcye/practica-wifi-segura/blob/main/Screenshot5.png)<a name="ancla6"></a>![](https://github.com/SEJ-notcye/practica-wifi-segura/blob/main/Screenshot6.png)

### Analisis

Tenemos muchas cosas para prestarle atencion a los datos proporcionados por el menu desarrollador, en primera instancia tenemos que la web usa el protocolo HTTP que se puede leer en el [encabezado de respuesta](#ancla5)
