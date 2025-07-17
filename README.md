# Guia rápido do projeto

## Data
Link dos dados [aqui](https://archive.ics.uci.edu/dataset/9/auto+mpg).

## Virtual Evironment
### Create Python environment

~~~bash
conda create -n auto_mpg python=3.10.12
conda activate auto_mpg
~~~

### Update Requirements List

~~~bash
pip freeze > requirements.txt
~~~

### Recreate Python environment with Requirements List

~~~bash
conda create -n auto_mpg python=3.10.12
conda activate auto_mpg
pip install -r requirements.txt
~~~