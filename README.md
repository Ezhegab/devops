- Зайти под root. 

- Сгенерировать ключ ssh-keygen по пути /root/.ssh

- Добавить id_rsa.pub ключ в /root/.ssh/authorized_keys

- Перейти в /etc

- Сделать git clone https://github.com/Ezhegab/ansible

- Запустить ansible-playbook main.yml

          Будут выполнены следующие действия:

          1. Инсталлируется Docker;
          2. Создастся пользователь `devops`;
          3. Закроется доступ по ssh `root` пользователю;
          4. Закроется доступ всем пользователям по ssh с помощью пароля;
          5. Включится фаервол и пропишутся правила для доступа извне
          только по 22 и 80 портам;
          6. coming soon...
          7. coming soon...




