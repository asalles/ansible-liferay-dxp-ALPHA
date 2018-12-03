ansible-liferay-dxp-ALPHA
========================
Ansible Playbook for: JBoss EAP 7.1 Standalone + Liferay 7 + Oracle 12c 

# Preparacion
```
copiar ssh-keys desde maquina de control
```
# Limpieza
```
killall java; rm -rf /opt/jboss-eap/ /etc/jboss-as /etc/systemd/system/jboss-eap.service /var/log/jboss-eap/ /etc/default/jboss-eap.conf /opt/liferay; ps -fea |grep java	
```


last update: Sun Dec  2 21:18:34 -03 2018
