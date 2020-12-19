# ansible-course

An extensive course in Ansible and configuration files.

## Ansible commands
--- Check if the system is up and running

**[acke@li1660-102 ~]$ systemctl status httpd**

> ● httpd.service - The Apache HTTP Server
>    Loaded: loaded (/usr/lib/systemd/system/httpd.service; disabled; vendor preset: disabled)
>   Drop-In: /usr/lib/systemd/system/httpd.service.d
>            └─php-fpm.conf
>    Active: inactive (dead)
>      Docs: man:httpd.service(8)


--- Start the system

**[acke@li1660-102 ~]$ sudo systemctl start httpd**


--- Allow communication to port 80

**[acke@li1660-102 ~]$ sudo firewall-cmd --add-port=80/tcp**

> success
