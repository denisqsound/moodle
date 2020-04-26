# moodle
Docker files for Moodle

# Как установить

- docker-compose up --build -d
- Создадутся два persist_volume (moodle и mariadb)
- Удостоверится что стартанула база
- Ждать пока в логах контейнера moodle не появится сообщение

[Sat Apr 25 22:37:54.065893 2020] [core:notice] [pid 96] AH00094: Command line: 'httpd -f /opt/bitnami/apache/conf/httpd.conf -D FOREGROUND'

- После этого приложение доступно на 1111 порту




Проблемы у Саши

- Необходимо сделать chmod 777 mariadb
