# How to install Django
To install Django, you must have Python installed, and a package manager like PIP.

PIP is included in Python from version 3.4.

## Django - Create Virtual Environment
It is suggested to have a dedicated virtual environment for each Django project, and one way to manage a virtual environment is venv, which is included in Python.

Here, aladin is the virtual environment

Windows: 

```bash
  py -m venv aladin
```

Unix/MacOS:

```bash
  python -m venv aladin
```

This will set up a virtual environment, and create a folder named "aladin" with subfolders and files, like this:

```bash
aladin
  Include
  Lib
  Scripts
  pyvenv.cfg
```  

Then you have to activate the environment, by typing this command:

Windows: 

```bash
  aladin\Scripts\activate.bat
```

Unix/MacOS:
```bash
  source aladin/bin/activate
```

Once the environment is activated, you will see this result in the command prompt:

Windows: 

```bash
  (aladin) C:\Users\Your Name>
```

Unix/MacOS:
```bash
  (aladin) ... $
```

## Install Django
Note: Remember to install Django while you are in the virtual environment!

Django is installed using pip, with this command:

Windows: 

```bash
  (aladin) C:\Users\Your Name>py -m pip install Django
```

Unix/MacOS:
```bash
  (aladin) ... $ python -m pip install Django
```

## Check Django Version
You can check if Django is installed by asking for its version number like this:


```bash
  (aladin) C:\Users\Your Name>django-admin --version
```

If Django is installed, you will get a result with the version number:
```bash
  4.1.2
```
