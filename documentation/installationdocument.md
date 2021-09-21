## Installation Document
### Crud Vue with PHP and Mysql

1. Instalar entorno virtual    
   
   ~~~
   pip install virtualenv
   ~~~

2. Crear el entorno virtual (venv es el nombre del entorno, sin embargo el nombre es opcional), se indica además que el entorno correrá con python3

    ~~~
    virtualenv -p python3 venv
    ~~~

3. Iniciar el entorno virtual

    ~~~
    source venv/bin/activate
    ~~~

4. Instalar Vue
    ~~~
    sudo npm install -g @vue/cli
    ~~~

5. correr el proyecto
   (Acceder al directorio del proyecto)
    ~~~
    npm run serve
    ~~~

6. Importar base de datos
7. Inicializar servidor web
   ~~~
    sudo /opt/lampp/lampp start
    ~~~