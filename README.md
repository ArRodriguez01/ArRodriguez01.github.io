Laravel en VPS

1.Creación de la suscripción y dominio temporal

 
 

Creamos una nueva suscripción con un proyecto vacío  donde crearemos nuestro proyecto laravel
2.Configuración bd y ssh
 
Creamos una base de datos que vinculamos al site nuevo creado
 
Modificamos las conexiones, para permitir usar la terminal al acceder con ssh

3.Creacion proyecto laravel
 
Mediante composer create-project crearemos un nuevo proyecto de laravel 
Y creamos un enlace simbólico del proyecto al httpdocs
 
 
Para habilitar los enlaces simbólicos entramos a la configuración de apache y nginx  y desmarcamos el limitar los enlaces simbólicos 
 

 
 
Crearemos un htaccess en la root del site y le asignamos permisos de ejecución para otros
 
 ![image](https://user-images.githubusercontent.com/115020442/217849614-59b8039a-d310-4629-b433-efd3b8fd061d.png)


