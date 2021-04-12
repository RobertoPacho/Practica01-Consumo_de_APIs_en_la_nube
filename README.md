# Practica01-Consumo_de_APIs_en_la_nube
Desarrollar una aplicación webusando una de lasAPI gratuitas de API List Fun. Tener en cuenta que se deben aplicar buenas prácticas para el desarrollo de la interfaz gráfica de usuario, para la cuál se permite utilizar plantilla deBootstrap.
Requisitos:
    • La aplicación Web debe permitir buscar la información a través de un nombre.
    • Además, se deberá visualizar toda la información disponible de la base de datos. 
    
    
  1. Identificar gráficamente la arquitectura web de la aplicación a desarrollar.
     ![imagen](https://user-images.githubusercontent.com/56565107/114470627-d2eb8100-9bb4-11eb-9900-bc63cb6df60b.png)
     
  2. Generar una llave para consumir los servicios web de la API (opcional, depende de la API seleccionada).
        - para generar la llave es necesario registrase en el sitio de la API a consumir si es requerido, una vez registrado le llegara un correo tal 
          y como se muestra en la imagen adjunta. 
       
        
        ![imagen](https://user-images.githubusercontent.com/56565107/114470781-15ad5900-9bb5-11eb-9264-a43064717ac7.png)


  3. Crear un repositorio en GitHub con el nombre “Practica01–Consumo de APIs en la nube”
        ![imagen](https://user-images.githubusercontent.com/56565107/114470945-61f89900-9bb5-11eb-8b33-b3dd372da58d.png)
        
  4. Desarrollar una aplicación con HTML + CSS + Javascript + Web Services para buscar información y visualizar toda la información disponible 
     a través de la API. 
     
     A) Creamos el código inicial html en donde se podrá visualizar la respuesta requerida.
    
        ![imagen](https://user-images.githubusercontent.com/56565107/114471075-a08e5380-9bb5-11eb-9cd2-8daf12121bb9.png)
        
        
        
        ◦ agregamos el titulo de nuestro sitio
        
        ◦ agregamos la opción de búsqueda ajax disponible mediante la Url
        
        ◦ agregamos el archivo contenedor de la función js que consumirá la API
        
        ◦ agregamos el archivo contenedor del estilo del sitio
        
      B) Creamos el archivo JS con la función que nos devolverá la petición que realicemos.
        
        ![imagen](https://user-images.githubusercontent.com/56565107/114471291-f8c55580-9bb5-11eb-8780-d103a628be6a.png)
        
        
        
        ◦ Creamos la variable data en la que se almacenara los datos solicitados.
        
        ◦ creamos la función que resivira como parametro la palabra que busquemos.
        
        ◦ En la linea 3 realizamos un get pasando la url de la api a consumir y la llave que nos da la app cundo nos registramos.
        
        ◦ Recuperamos los datos de la consulta y la almacenamos en la variable rawstring.
        
        ◦ Para poder manipular los datos recibidos hacemos un parse a JSON.
        
        ◦ Ahora sacamos el titulo,año y url de los detalles de la pelicula y la mostramos por medio document.getElementById("respuesta").innerHTML. 
        
        
      C) Creamos el archivo css para el diseño de la pagina web
      
        ![imagen](https://user-images.githubusercontent.com/56565107/114471498-5eb1dd00-9bb6-11eb-8e8b-eb517a688b32.png)

        
        ◦ Cabíamos el color del cuerpo del sitio web.
        
        ◦ Centramos el contenido y cambiamos el color.
        
        ◦ Alineamos el contenido al centro.

  5. Vista
      - caja para ingresar el contenido a buscar.
      
      ![imagen](https://user-images.githubusercontent.com/56565107/114471632-91f46c00-9bb6-11eb-853b-dedd4a343533.png)
      
      - vista de resultado

        ![imagen](https://user-images.githubusercontent.com/56565107/114471696-a9cbf000-9bb6-11eb-83d1-33a41ffe1997.png)
        
  6. Realizar varios commits en la herramienta GitHub que demuestren el desarrollo de la aplicación.
  
        ![imagen](https://user-images.githubusercontent.com/56565107/114471869-e7c91400-9bb6-11eb-8eed-2e1b44874f0c.png)

        - commits realizados
        
        ![imagen](https://user-images.githubusercontent.com/56565107/114471911-f7485d00-9bb6-11eb-981b-fdac6fdc66f8.png)

RESULTADO(S) OBTENIDO(S):
 El consumo de la API web Omdb fue exitosa 
 
CONCLUSIONES:
El uso de las api son muy útiles ya que obtenemos datos ya recopilados y nos ayuda a reducir el código para mostrar el contenido que buscamos. 
Enlace git:
https://github.com/RobertoPacho/Practica01-Consumo_de_APIs_en_la_nube 

RECOMENDACIONES:
Para realizar el consume de una api debemos saber cuales son los requerimientos necesarios para ello, para consumir la API Omdb en necesario tener un clave que que se nos enviá al correo electrónica después de registrarnos.

        
        


