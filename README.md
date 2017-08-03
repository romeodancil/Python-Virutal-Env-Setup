### Python Virtual Env Setup ###
``` bash
$ mkdir tutorial
```
``` bash
$ cd tutorial
```
### Create a virtualenv to isolate our package dependencies locally ###
``` bash
$ pip install virtualenvwrapper
```
``` bash
$ export WORKON_HOME=~/Envs
```
``` bash
$ mkdir -p $WORKON_HOME
```
``` bash
$ source /usr/local/bin/virtualenvwrapper.sh
```
``` bash
$ mkvirtualenv env1
```
### Virtualenvwrapper source ###
https://virtualenvwrapper.readthedocs.io/en/latest/

### Then you can now start installing your python requirements ###
#### To view all the requirements ##
``` bash
$ pip freeze
```
