Python.PH Memberships
=====================
## Background/Objectives
The main purpose of this app is to collect PythonPH member information. We imagine it being integrated to other PythonPH apps such as jobs.python.ph, etc. in the future.


## Prerequisites

TODO


### External libs for Pillow

See: https://pillow.readthedocs.org/en/latest/installation.html#simple-installation

```
$ sudo apt-get install libtiff4-dev libjpeg8-dev zlib1g-dev libfreetype6-dev liblcms2-dev libwebp-dev tcl8.5-dev tk8.5-dev python-tk
```


### Virtualenv

You should have a virtualenv ready with either Python 2.7.x or 3.x


### Database

This app is configured with PostgreSQL/MySQL in mind.


### Configuration

Under your project's settings folder you'll find a `config.json` file. Fill it out with the needed
values. Alternatively you can also create a `config-user.json` for configurations specific to a
particular environment.

