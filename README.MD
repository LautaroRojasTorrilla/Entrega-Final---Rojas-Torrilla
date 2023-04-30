# _Space Planets_

#### By _**Lautaro Rojas Torrilla**_

#### _Aplicación de Python con tecnología django para crear Sistemas Planetarios y Civilizaciones en el universo_

## Technologies Used

* _PYTHON_
* _DJANGO_
* _HTML_
* _CSS_

## Description

_El sitio web permite a usuarios administradores, crear, editar, ver y eliminar sistemas planetarios, estrellas, planetas y/o habitantes.
Podes crear tanto como tu imaginación lo permita._

_Tenés la magnífica posibildad de generar Sistemas planetarios con determinadas clases de estrellas, colocar enésimas cantidades de estrellas que desees yla cantidad de planetas que orbitan esa/s magníficas estrella/s._

_Además crear habitantes para estos planetas, setear su idioma y modificar el planeta en el que residen._

## Setup/Installation Requirements

* _Verificar los requerimientos en el archivo requirements.txt y utilizar el mismo para la instalación de librerias_
* _Es recomendable descargar el código completo desde github haciendo un pull, para tomar como ejemplo la base de datos_
* _Por otro lado, en el caso de que haya conflicto con la instalación de los requeriments, recomiendo que se cree un entorno virtual
    y se instalen los requisitos uno por uno, de la siguiente manera:
    pip install asgiref==3.5.2
    pip install certifi==2022.9.14
    pip install charset-normalizer==2.1.1
    pip install decorator==5.1.1
    pip install dj-database-url==1.0.0
    pip install Django==4.1
    pip install django-bootstrap-icons==0.8.1
    pip install gunicorn==20.1.0
    pip install idna==3.4
    pip install Pillow==9.2.0
    pip install psycopg2==2.9.3
    pip install requests==2.28.1
    pip install sqlparse==0.4.2
    pip install tzdata==2022.2
    pip install urllib3==1.26.12
    pip install whitenoise==6.2.0
    _



* _El correcto uso es en primer lugar, tener un usuario administrador o Staff para poder hacer los proximos pasos, ya que estos mismos estan limitados a cada perfil (en el presente caso es admin admin)_
* _La creación de un nuevo Sistema comienza con la creación en la solapa CARACTERISTICAS de al menos una CLASE ESTRELLA y un CLASE PLANETA.._
* _Luego, deberan crear en la solapa SISTEMAS PLANETARIOS, un sistema planetario que tomará de referencia la clase de estrella que contendra la clase de estrella que posee este sistema planetario (por el momento solo se puede cargar un solo tipo de estrella)_
*  El siguiente paso se encuentra dentro de la Solapa Estrella, crear una Estrella donde podras elegir el sistema planetario al que pertenece_
* _A continuación será posible agregar un planeta o no, si es que se quiere crear Habitantes, los mismos requieren tener un planeta creado para que se pueda cargar la opción Planeta Natal y Habitando Planeta_ 
* Finalmente, está la posibilidad de consultar por el momento, los habitantes con determinado apellido o tambien, todos los habitantes que existan_



## Known Bugs

* _No he encontrado bug alguno en el funcionamiento_

## License

_Licencia_

Copyright (c) _30/04/2023_ _lautaro Rojas Torrilla_