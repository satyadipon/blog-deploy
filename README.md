### 📁 Project Structure:

blog_deploy/
- inventory
- playbook.yml
- templates/nginx.conf.j2
- app/index.html
- app/style.css


## How to deploy the website?
- Run the ansible playbook
```
ansible-playbook -i inventory playbook.yml
```
- Open the browser and visit:
```
http://<remote-server-ip>/
```