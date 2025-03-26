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

python -m venv ~/path_to_your_folder/.venvs/my_first_env
Útil si prefieres organizar tus entornos virtuales en un directorio centralizado, en lugar de tenerlos dentro de cada proyecto.

source env/bin/activate
Verificar que estemos dentro del entorno virtual

which python3
Instalar la dependencia dentro del entorno virtual

pip3 install requests
Verificar la instalacion

pip3 freeze
Crear el archivo para que cualquier persona pueda desplegar el proyecto

pip freeze > requeriments.txt
