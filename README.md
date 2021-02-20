# CLI | Python

## Requerimientos

Para comenzar con el CLI de pip obiemente necesitarias tener [python](https://python.org).

### pip - instalacion

¿Como seria el comando?

El comando es bastante sencillo pero para estar mas seguros sobre las versiones de los otros modulos seria recomendable untilizar un `virtual` enviroment.
cv
Para crearse un `virtual enviroment` habria que hacer estos pasos.

Lo primero seria instalarte global mente un modulo llamado [venv](https://pypi.org/project/virtualenv/) en el que se instalaria asi.

```
$ pip install virtualenv
...
```

Una vez ya instalado estamos preparados para crearnos un virtual enviroment.

```
$ python3 -m venv env
```

**NOTA**: como podeis ver en el comando ponermos `env` al final. Eso se puede cambiar por el nombre que querrais como por ejemplo `venv` cuanto mas comun mejor :)

Para activarlo seria muyyyyyyyy facil.

Windows:

```
$ env/Scripts/activate
```

Linux:
```
$ source env/bin/activate
```

Muy bien. Ya estamos preparados con un `virtual enviroment` activado y listo para instalar cosas con el. El comando de instalacion como poner muy claramente seria con `pip` y se escribiria con la siguiente linea.

```
$ pip3 install HostHome-cli
```

La gente suele tener algunos errores al instalar modulos con pip en windows ya que algunos estan preparados para linux. Si quieres que se instale sin ningun error para windows ejecuta las siguientes lineas.

```
$ pip install pipwin
$ pipwin install HostHome-cli
```

Si sigues teniendo error contacta con algun trabajador en [HostHome](https://github.com/HostHome-oficial)

![img](https://raw.githubusercontent.com/HostHome-of/website/main/src/static/images/cli-pip.png)
