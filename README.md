#Laravel en VPS

1.Creación de la suscripción y dominio temporal
![image](https://user-images.githubusercontent.com/115020442/217850075-c880018d-6feb-4519-9f5e-f2c616407483.png)
![image](https://user-images.githubusercontent.com/115020442/217850091-9f752abd-6501-4bbe-9b6a-a3baea189ee7.png)

 
 

Creamos una nueva suscripción con un proyecto vacío  donde crearemos nuestro proyecto laravel
2.Configuración bd y ssh
 ![image](https://user-images.githubusercontent.com/115020442/217850115-bd1c8484-6a5c-41ca-afea-600af2eb87f9.png)

Creamos una base de datos que vinculamos al site nuevo creado
 ![image](https://user-images.githubusercontent.com/115020442/217850153-3c205d04-c95d-4842-97a6-7635ae8d3c11.png)

Modificamos las conexiones, para permitir usar la terminal al acceder con ssh

3.Creacion proyecto laravel
 ![image](https://user-images.githubusercontent.com/115020442/217850175-44a315bd-5587-456f-9f4c-4581638f72f6.png)

Mediante composer create-project crearemos un nuevo proyecto de laravel 
Y creamos un enlace simbólico del proyecto al httpdocs
 ![image](https://user-images.githubusercontent.com/115020442/217850202-c7d9e5ec-55c1-46a7-a1b4-c0dab5c22e67.png)
![image](https://user-images.githubusercontent.com/115020442/217850217-abbe9f29-700b-4c1c-b085-fb06d894e8ea.png)

 
Para habilitar los enlaces simbólicos entramos a la configuración de apache y nginx  y desmarcamos el limitar los enlaces simbólicos 
 ![image](https://user-images.githubusercontent.com/115020442/217850239-386dccfd-3ee7-48b6-a3e4-e3f4be9e13a3.png)
![image](https://user-images.githubusercontent.com/115020442/217850255-233fb3bf-85db-4bb1-97ac-f37e66d4f022.png)
![image](https://user-images.githubusercontent.com/115020442/217850304-756df604-46e9-42b3-bf9f-c4bb62734e26.png)


 
 
Crearemos un htaccess en la root del site y le asignamos permisos de ejecución para otros
 ![image](https://user-images.githubusercontent.com/115020442/217850338-14add49b-a7c9-4400-af17-4333c439e76b.png)

 ![image](https://user-images.githubusercontent.com/115020442/217849614-59b8039a-d310-4629-b433-efd3b8fd061d.png)


