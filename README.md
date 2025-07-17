# auto_mpg

## 

### Data
Link dos dados [aqui](https://archive.ics.uci.edu/dataset/9/auto+mpg).

### Install the ucimlrepo package
~~~python
pip install ucimlrepo
~~~

### Import the dataset into your code 
~~~python
from ucimlrepo import fetch_ucirepo 
  
# fetch dataset 
auto_mpg = fetch_ucirepo(id=9) 
  
# data (as pandas dataframes) 
X = auto_mpg.data.features 
y = auto_mpg.data.targets 
  
# metadata 
print(auto_mpg.metadata) 
  
# variable information 
print(auto_mpg.variables) 
~~~

## Virtual Evironment
### Create Python environment

~~~bash
conda create -n auto_mpg python=3.10.12
conda activate auto_mpg
pip freeze > requirements.txt
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