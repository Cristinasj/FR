# FR-
Apuntes de fundamentos de redes
|Protocolo|Siglas|Uso|Capa|Puerto|
|---------|------|---|----|------|
|POP3|Post Office Protocol|Email. Borra los emails del servidor de correo|Aplicación|110, 995 con SSL/TLS|
|IMAP|Internet Message Access Protocol|Email. Mejor sincronización (lectura, borrado...) que POP3 porque el sevidor guarda una copia maestra|Aplicación|143, 993 con SSL/TLS|
|SSL|Secure Socket Layer|Criptografía|Apliación||
|TLS|||Aplicación||
|BGP|||Aplicación||
|DHCP(v6)||Configuración automática de parámetris de red|Aplicación|66,67,68|
|DNS||Resolución de nombres de domimio|Aplicación|53|
|FTP||Transferencia de archivos|Aplicación|20,21|
|HTTP||Transferencia de hipertexto|Aplicación|80,443 con SSL/TLS|
|IMAP|||Aplicación||
|OSPF|||Aplicación||
|PTP|||Aplicación||
|RIP|||Aplicación||
|SMTP||Email|Aplicación|25|
|SNMP|||Aplicación||
|SSH|||Aplicación||
|Telnet||cliente/servidor|Aplicación|23|
|TCP|||Transporte||
|UDP||Intercambio de datagramas a través de una red|Transporte|113|
|IP|||Internet||
|ICMP|||Internet||
|ARP|||Enlace||
|PPP|||Enlace||
|MAC|||Enlace||
|Tunnels|||Enlace||
||||||
Puertos bien conocidos: 0-1023 críticos
Puertos registrados: 1024-49151 IANA, aplicaciones no críticas
Puertos efimeros: 49152-65535 Son de usar y tirar. Funciona mientras dura la conexión
