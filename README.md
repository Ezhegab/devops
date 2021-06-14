Зайти под root. 
Сгенерировать ключ ssh-keygen по пути /root/.ssh
Добавить id_rsa.pub ключ в /root/.ssh/authorized_keys
Перейти в /etc
Сделать git clone https://github.com/Ezhegab/ansible
Запустить ansible-playbook main.yml
