# How to Use GAE
## Django deploy on standard GAE
### required codes
1. django framework codes
2. requirements.txt
3. main.py 
4. app.yaml

### 1. django framework codes
Create django project on usual</br>
But allow any ip addres by changing into ALLOWED_HOST=['*']

### 2. requirements.txt
Make file for telling using ptyhnon libraries to GAE

### 3. main.py
Nginx on GAE communicate with wsgi </br>
from [project_name].wsgi import application </br> 
app = application

### 4. app.yaml
Configulation file of GAE</br>
runtime: python38 </br>
service: [service_name]

### How to debug
$gcloud app logs read
