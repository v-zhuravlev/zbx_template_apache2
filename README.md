These Apache templates are now part of official Zabbix distribution, please use them instead if you have Zabbix 4.2 or later:

- [HTTP agent template](https://git.zabbix.com/projects/ZBX/repos/zabbix/browse/templates/app/apache_http)
- [Zabbix agent template](https://git.zabbix.com/projects/ZBX/repos/zabbix/browse/templates/app/apache_agent)

# zbx_template_apache2

Template App Apache2 for Zabbix 4.0 that works without any external scripts.  
You can poll Apache2 using Zabbix agent locally(Template App Apache2 Zabbix agent) or poll it directly from Zabbix server/proxy(Template App Apache2 HTTP). Choose template that better suits you.  Tune URL with user macros if required.  
## Setup Apache2

see https://httpd.apache.org/docs/current/mod/mod_status.html

## Sample

![image](https://user-images.githubusercontent.com/14870891/47022436-299fad80-d166-11e8-934a-0c9cee4c694d.png)
