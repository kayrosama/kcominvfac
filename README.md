# APIBASE
(NOTA: Aun en construccion)
Cascaron de APIS con CRUD de usuarios para partir de este codigo.

# Pasos para instalar el Sistema

# Instaladores
| Nombre                   | Instalador                                            |
|:-------------------------|:------------------------------------------------------| 
| `Compilador`             | Python3                                               |
| `IDE de programación`    | Visual Studio Code , Sublime Text , Atom , Vim , etc. |
| `FrameWorks`             |  [Django](https://www.djangoproject.com/ "Django") , [Django REST](https://www.django-rest-framework.org/ "Django REST")               |
| `Motor de base de datos` | MySQL , PostgreSQL , Sqlite3                          |

##### Pasos de instalación

Linux:

```bash

git clone https://github.com/kayrosama/apibase.git
cd apibase
apt-get install -f -y python3-pip python3-venv
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip
python3 -m pip install -r requirements.txt 
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py createsuperuser
python3 manage.py runserver
http://127.0.0.1:8000/
CONTROL-C

```

##### Sugerencia para crear el super usuario en aplicacion

```bash

http://127.0.0.1:8000/admin

username: admin
email: master@apibase.com
password: adm123

```

------------

#  ありがとう

***KSM, 2024.***

