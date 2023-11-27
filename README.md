# ansible-role-nginx
Ansible роль установки веб сервера nginx на ОС Ubuntu.

mkdir ~/ansible/ && cd ~/ansible

git clone https://github.com/pomidor2007/ansible-role-nginx.git

В файле ~/ansible/host_vars/nginx прописать параметры сервера ( ip, user, pass ), на который необходимо установить nginx.

cd ~/ansible/

ansible-playbook -i inventory nginx.yml






