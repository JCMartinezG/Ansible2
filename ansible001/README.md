# Cofiguración de Ansible


webserver.yml --> Nginx to server01 0.0.0.0:2221->22/tcp, 0.0.0.0:8000->80/tcp

sqlserver.yml --> MySQL to server02 0.0.0.0:3306->3306/tcp, 0.0.0.0:2222->22/tcp

nosqlserver.yml --> Redis to server03 0.0.0.0:6379->6379/tcp, 0.0.0.0:2223->22/tcp

tarea.yml --> Nginx, MySQL, Redis.
