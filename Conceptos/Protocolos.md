# Protocolo ARP
Se utiliza para resolver una dirección IP de la capa de Red (Capa 3) en un direccion MAC de capa de enlace (Capa 2).

<h3>Solicitud ARP</h3><br>
Cuando un dispositivo desea comunicarse con otro en una LAN, envía una solicitud ARP para convertir la dirección IP del dispositivo de destino en su dirección MAC. La solicitud se transmite a todos los dispositivos de la LAN y contiene la dirección IP del dispositivo de destino. El dispositivo con la dirección IP coincidente responde con su dirección MAC. 

<h3>Respuesta de ARP</h3><br>
Cuando un dispositivo recibe una solicitud ARP, envía una respuesta ARP al dispositivo solicitante con su dirección MAC. El mensaje de respuesta contiene las direcciones IP y MAC tanto del dispositivo solicitante como del dispositivo que responde. 

<hr style="height:5px; border:none; color:#333; background-color:#333;" /> 

## Tabla de Protocolos y Puertos Comunes TCP

| Protocolo | Acrónimo | Puerto | Descripción |
| :--- | :--- | :--- | :--- |
| **Telnet** | Telnet | 23 | Servicio de inicio de sesión remoto. |
| **Secure Shell** | SSH | 22 | Servicio de inicio de sesión remoto seguro. |
| **Simple Network Management Protocol** | SNMP | 161-162 | Gestión de dispositivos de red. |
| **Hyper Text Transfer Protocol** | HTTP | 80 | Transferencia de páginas web. |
| **Hyper Text Transfer Protocol Secure** | HTTPS | 443 | Transferencia segura de páginas web. |
| **Domain Name System** | DNS | 53 | Resolución de nombres de dominio. |
| **File Transfer Protocol** | FTP | 20-21 | Transferencia de archivos. |
| **Trivial File Transfer Protocol** | TFTP | 69 | Transferencia simple de archivos. |
| **Network Time Protocol** | NTP | 123 | Sincronización de relojes de computadora. |
| **Simple Mail Transfer Protocol** | SMTP | 25 | Transferencia de correo electrónico. |
| **Post Office Protocol** | POP3 | 110 | Recuperación de correos electrónicos. |
| **Internet Message Access Protocol** | IMAP | 143 | Acceso a correos electrónicos. |
| **Server Message Block** | SMB | 445 | Transferencia de archivos en red local. |
| **Network File System** | NFS | 111, 2049 | Montaje de sistemas remotos. |
| **Bootstrap Protocol** | BOOTP | 67, 68 | Arranque remoto de computadoras. |
| **Kerberos** | Kerberos | 88 | Autenticación y autorización. |
| **Lightweight Directory Access Protocol** | LDAP | 389 | Servicios de directorio. |
| **RADIUS** | RADIUS | 1812, 1813 | Autenticación y autorización remota. |
| **Dynamic Host Configuration Protocol** | DHCP | 67, 68 | Configuración de direcciones IP. |
| **Remote Desktop Protocol** | RDP | 3389 | Acceso a escritorio remoto. |
| **Network News Transfer Protocol** | NNTP | 119 | Acceso a grupos de noticias. |
| **Remote Procedure Call** | RPC | 135, 137-139 | Llamada a procedimientos remotos. |
| **Identification Protocol** | Ident | 113 | Identificación de procesos de usuario. |
| **Internet Control Message Protocol** | ICMP | 0-255 | Resolución de problemas de red (Ping). |
| **Oracle DB Listener** | oracle-tns | 1521/1526 | Recibe solicitudes de clientes Oracle. |
| **Squid Web Proxy** | http-proxy | 3128 | Proxy de caché para acelerar servidores web. |
| **Secure Copy Protocol** | SCP | 22 | Copia segura de archivos entre sistemas. |
| **Session Initiation Protocol** | SIP | 5060 | Sesiones de voz sobre IP (VoIP). |
| **Microsoft SQL Server** | ms-sql-s | 1433 | Conexiones de clientes a MS SQL Server. |
| **Point-to-Point Tunneling Protocol** | PPTP | 1723 | Creación de redes privadas virtuales (VPN). |
| **Remote Execution** | REXEC | 512 | Ejecución de comandos en computadoras remotas. |
| **Remote Login** | RLOGIN | 513 | Inicia una sesión de shell interactiva remota. |
| **X Window System** | X11 | 6000 | Interfaz gráfica de usuario para redes. |
| **DB2 RDBMS** | DB2 | 50000 | Gestión de bases de datos relacionales empresariales. |


<hr style="height:5px; border:none; color:#333; background-color:#333;" /> 

## Tabla de Protocolos y Puertos Comunes UDP

| Protocolo | Acrónimo | Puerto | Descripción |
| :--- | :--- | :--- | :--- |
| **Domain Name System** | DNS | 53 | Resuelve nombres de dominio en direcciones IP. |
| **Trivial File Transfer Protocol** | TFTP | 69 | Transferencia de archivos entre sistemas. |
| **Network Time Protocol** | NTP | 123 | Sincroniza los relojes de las computadoras en red. |
| **Simple Network Management Protocol** | SNMP | 161 | Supervisa y gestiona dispositivos de red de forma remota. |
| **Routing Information Protocol** | RIP | 520 | Intercambio de información de enrutamiento. |
| **Internet Key Exchange** | IKE | 500 | Intercambio de claves para comunicaciones seguras. |
| **Bootstrap Protocol** | BOOTP | 68 | Se utiliza para iniciar hosts en una red. |
| **Dynamic Host Configuration Protocol** | DHCP | 67 | Asignación dinámica de direcciones IP. |
| **Telnet** | TELNET | 23 | Protocolo de acceso remoto basado en texto. |
| **MySQL** | MySQL | 3306 | Sistema de gestión de bases de datos de código abierto. |
| **Terminal Server** | TS | 3389 | Acceso remoto predeterminado en Windows. |
| **NetBIOS Name Service** | netbios-ns | 137 | Resuelve nombres NetBIOS en direcciones IP (LAN). |
| **Microsoft SQL Server** | ms-sql-m | 1434 | Servicio del explorador de Microsoft SQL Server. |
| **Universal Plug and Play** | UPnP | 1900 | Descubrimiento y comunicación entre dispositivos. |
| **PostgreSQL** | PGSQL | 5432 | Sistema de gestión de bases de datos objeto-relacionales. |
| **Virtual Network Computing** | VNC | 5900 | Sistema gráfico para compartir escritorio. |
| **X Window System** | X11 | 6000-6063 | Proporciona interfaz gráfica (GUI) en sistemas Unix. |
| **System Log** | SYSLOG | 514 | Estándar para recopilar y almacenar mensajes de registro. |
| **Internet Relay Chat** | IRC | 194 | Comunicación de texto (chat) en tiempo real. |
| **OpenPGP** | OpenPGP | 11371 | Cifrado y firma de datos y comunicaciones. |
| **Internet Protocol Security** | IPsec | 500 | Proporciona comunicación segura y cifrada (VPN). |
| **X Display Manager Control Protocol** | XDMCP | 177 | Inicio de sesión remoto en computadoras con X11. |