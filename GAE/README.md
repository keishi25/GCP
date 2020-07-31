# How to Use GAE
## Django deploy on GAE
### required codes
1. natural django framework codes
2. requirements.txt
3. main.py 
4. app.yaml

### 1. natural django framework codes
Create project on usual

### 2. requirements.txt
Make file for telling using ptyhnon libraries to GAE

### 3. main.py
Nginx on GAE communicate with wsgi </br>
'''from [project_name].wsgi import application'''</br>
'''app = application'''

### 4. app.yaml
Configulation file of GAE</br>
'''runtime: python38'''</br>
'''service: [service_name]'''
