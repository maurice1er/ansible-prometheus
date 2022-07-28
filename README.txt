# Pre-requis
```
Config 2F factor with your gmail account
Create api token 

Add as tag on your backend server: Project:Udapeople (you can change tag key and value into playbook.yml -> vars -> prometheus)
```

# download unzip 
``` sh 
sudo apt install unzip -y
unzip alertmanager
cd alertmanager
```

# change playbook.yml
```
to: #email:change me
from: #email:change me
auth_password: #gmail api token:change me
```

``` sh
sudo chmod +x setup.sh
./setup.sh
``` 
