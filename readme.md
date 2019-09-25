crear un entorno de python

    pip install virtualenv

    virtualenv Flask -p C:\Python\Python37\python.exe

Activar enviroment

MAC:

    source Flask/bin/activate

WIN:

    ./Flask/Scripts/activate.bat

PowerShell:

    ./Flask/Scripts/activate.ps1

Instala Flask:

    pip install flask

El archivo requirements.txt tiene las libererias base que cargara docker en el contenedor para correr

    docker build -t capitulo_1 .

Para ejecutar la aplicación

    docker run -p 5000:5000 capitulo_1
