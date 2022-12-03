# Proyecto Bot #1

## Desarrolladores

| Rol | Nombre | Correo |
| --- | --- | --- |
| Desarrollador #1 | Jorge I. Meza | jimezam@autonoma.edu.co |
| Desarrollador #2 | Gusanito | gusanito@autonoma.edu.co |

## Opciones 

1. Start
1. Help
2. About
1. Sumar a y b
1. Dividir a y b

## Instalación

```
$ git clone https://github.com/jimezam/bot1pads2022.git

$ cd bot1pads2022
```

Crear el archivo `.env` y agregar el siguiente contenido.  Tener en cuenta que se deben reemplazar las `xxx` por el **token** asignado por `@BotFather`.

```
TELEGRAM_TOKEN = "xxx" 
```

Para crear el ambiente e instalar las librerías ejecutar los siguientes comandos.

```
$ python -m venv env

$ source env/bin/activate

$ pip install -r requirements.txt
```

## Ejecución

```
$ python bot.py
```

