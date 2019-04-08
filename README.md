# ansible_zabbix
Instalação do zabbix com ansible


 Varaiveis para alteração em roles roles/install/vars/mail.yml
---
  2 pass_db_zabbix:
  3   zabbix
  4 
  5 host_db_zabbix:
  6   localhost
  7 
  8 php_time_zone:
  9   America/Sao_Paulo
 10 
 11 mysql_root_pass:
 12   suasenhamysql
