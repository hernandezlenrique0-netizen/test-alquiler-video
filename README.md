# test-alquiler-video
Este proyecto implementando una API REST para una tienda virtual de videos (venta.alquiler), construida con lenguaje python y el fremwork FastApi. El objetivo es gestionar un catalago de discos (peliculas o videos digitales ) juntos con las operaciones de usuarios, ventas y alquiler.

##Estructura del proyecto 
|-- Main.py # Punto de entrada de la aplicación de la Api, FastAPI
|

entidades/         #Directorio de paquetes de contiene todas las clases
   |-__init__.py
   |-disco.py
   |-usuario.py
   |-venta.py
   |-renta.py
   |-catalogo.py

##Instalació y ejecución
   1.Clonar el repositorio
     git clone https://github.com/usuario/test-alquiler-video.git
   2.cd test-alquiler.video
   3.crear y activar entorno virtual (opcional, recomendado)
   4.python -m venv venv
   5.source venv/bin/activate #linux/Mac
   6.venv/scripts\activate    #Windows
   7.Instalar dependencias
     7.1 pip install fastapi uvicorn pydantic
   8.Ejecutar el servidor
     8.1 uvicorn main:app --reload
   9.Acceder a la API
   10.Acceder a la API
     *Documebtación interactiva: http//127.0.0.1:8000/docs
     *Docuemtación anternativa (ReDoc):http://127.0.0.1:8000/redoc

  ##Endpoints principales    (versión inicial)
  Metodo       Enpoints       Descripción
  GET          /discos/       Lista de los discos disponibls
  POST         /discos/       agregar un nuevo disco
  PUT          /discos/{id}   Actualizar información de un disco
  DELETE       /discos/{id}   Eliminar un disco
  POST         /usuario/      Resgsitra un nuevo usuario
  POST         /ventas/       Resgistrar ventas
  POST         /rentas/       Registra alquileres

  ##Tecnologia Utilizdas
  * Python 3.12.8
  * FastApi
  * Uvicorn (servidor ASGI)

  ##Proyecto desarrollado como casa de estudio
  * Nombre :* Luis Enrique Hernández Lorío.** <hernandezlenrique0@gmail.com>
  * Github :hernandezlenrique0-netizen
     
   
