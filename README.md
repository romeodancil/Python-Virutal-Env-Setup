### Python Virtual Env Setup ###
``` bash
$ mkdir tutorial
```
``` bash
$ cd tutorial
```
### Create a virtualenv to isolate our package dependencies locally ###
``` bash
$ virtualenv env
```
``` bash
$ source env/bin/activate
```
``` bash
$ pip install django
```
``` bash
$ django-admin.py startproject tutorial
```
``` bash
$ cd tutorial
```
``` bash
$ django-admin.py startapp quickstart
```
``` bash
$ cd quickstart
```
### Virtualenvwrapper source ###
https://virtualenvwrapper.readthedocs.io/en/latest/

### Python3 venv
``` bash
$ python3 -m venv myenv
``` bash
$ source env/bin/activate
```
``` bash
$ source env/bin/activate
```

### Then you can now start installing your python requirements ###
#### To view all the requirements ##
``` bash
$ pip freeze
```
