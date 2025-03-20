# Game Project

Para correr el juego debes seguir las siguientes instrucciones en la terminal

'''sh
cd game 
python3 main.py
'''

# App Project
´´´
sh
git clone
cd app
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
´´´

# Con más detalles
Crear un entorno

python3 -m venv env
Activar un entorno virtual

source env/bin/activate
Verificar que estemos dentro del entorno virtual

which python3
Instalar la dependencia dentro del entorno virtual

pip3 install requests
Verificar la instalacion

pip3 freeze
Crear el archivo para que cualquier persona pueda desplegar el proyecto

pip freeze > requeriments.txt