# Flask

## P2_PagImg

### Descripcion
Proyecto consiste en la creacion de un pagina de imagenes utilizando postgress

### Pasos para ejecutar el proyecto
- Ingresar a cmd y verificar que se cuenta con `virtualenv`
- En caso de no tenerlo, instalar con el comando `pip install venv`
- Crear un entorno virtual desde el cmd teniendo en cuenta la ruta del repositorio del proyecto
- En el `cmd` ejecutar: `python -m venv (ruta del repositorio)\ env `
- Abrir el IDE de preferencia y proceder a activar el entorno virtual creado `env`
### Pasos para activar el env
- Ubicarnos en el la rutal del repositorio y dirigirnos a la carpeta `env`
- Luego ejecutamos `Scripts\activate`
- Una vez iniciado `env`, procedemos a instalar `requirements.txt` mendiante `pip install -r requirements.txt`
- Luego en la ruta de nuestro repositorio dirigirnos a la carpeta donde se encuetra el proyecto y ejecutar `python app.py`

### Pagina de ayuda para la base de datos
https://stackoverflow.com/questions/27900018/flask-sqlalchemy-query-join-relational-tables

### Pagina de ayuda para carga de imagenes en flask
https://flask.palletsprojects.com/en/2.0.x/patterns/fileuploads/

https://roytuts.com/upload-and-display-multiple-images-using-python-and-flask/