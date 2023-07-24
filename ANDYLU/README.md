Acontinuación muestro algunos pasos para hacer correr el proyecto:
PASO 1:
Crear mi entorno virtual

 virtualenv -p python3 env o  python3 -m venv env

PASO 2: Activar el entorno virtual ejecutando
. env/Scripts/activate

PASO 3:
Ya dentro del entorno virtual puedes instalar flask con el comando:

`pip install flask`
PASO 4:
Instalar Python MySQL Connector, es una bibliote (Driver) para conectar Python con MySQL, instalar con el siguiente comando:

` pip install mysql-connector-python`

PASO 5:
Instalar Python WTF Connector, es una bibliote (Driver) para conectar Python con Inicio de secciones, instalar con el siguiente comando:

` pip install flask-WTF`
IMPORTANTE :
Puedes solo crear tu entorno virtual y posicionarte en el mismo, luego ejecutar el siguiente comando:

pip install -r requirements.txt

en el mismo se encuentran todas las dependecias del proyecto.