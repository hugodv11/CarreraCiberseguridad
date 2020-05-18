# Carrera Ciberseguridad  

##  Introducción a Ethical Hacking  

 **-Introducción:**  
 En este módulo se presenta al profesor y se hace una breve introducción de que es la *CiberSeguridad* y de que trata el *Ethical Hacking*  
 
 **-Cifrado y PKI:**  
 En este módulo de la materia se habla de los tipos de *cifrado*, de las *huellas digitales*, los *certicados digitales*,
 del *PKI(Infraestructura de clave pública)* y de las *autoridades de certificación(CA)*, como están organizadas y como trabajan.  
 
 **-Netfilter e Iptables:**  
 En la primera parte de este módulo se habla sobre *Netfilter*, los *Firewalls(Cortafuegos)*, el *enmascaramiento NAT* y como se filtran
 los paquetes, que cadenas siguen y que tipos de procedimientos se deben aplicar a los paquetes en cada paso(Iptables).  
 En la segunda parte se explica como crear reglas utilizando el comando iptables y posteriormente 
 se propone una practica que consiste en 4 dispositivos, uno representa un ordenador en una red desconocida, otros dos terminales
 que están conectados a una red conocida, como podría ser la red de nuestra empresa y el ultimo dispositivo actua como firewall
 donde cambiamos/creamos reglas para decidir por donde deberían ir los paquetes y si permitimos o no la comunicación del dispositivo
 que esta fuera de nuestra red con los servicios de nuestra empresa(por ejemplo con una web que tengamos alojada en uno de los ordenadores
 de nuestra red).  
 
 **-Descubrimiento de puertos y servicios:**  
 Se explica como utilizar la herramienta *NMAP*, que sirve para escanear dispositivos y descubrir que puertos están abiertos y que servicios
 están en escucha en los mismos a parte de más información(SO, versiones...).  
 Al ser NMAP una herramienta peligrosa ya que es ilegal escanear empresas o entidades sin permiso y puede acarrear muchos problemas
 se expone otra alternativa: *Shodan*, que cuenta con escaneos pasivos(escaneos que hace la propia Shodan y que tu puedes consultar de
 forma gratuita).  
 
 **-Ataques sobre servicios:**  
 En este módulo se exponen tres tipos de ataques:  
 - *Fuerza bruta*: Consiste en conseguir un par usuario-contraseña probando gran cantiddad de combinaciones hasta conseguir el correcto.  
 - *Inyecciones SQL*: Consiste en infiltrar código sql cuando existe una falta de validación de campos a la hora de procesar operaciones en 
 una base de datos.  
 - *XSS*: Está dirigido a páginas web y consiste en inyectar código HTML y Javascript sin que sea validado para conseguir algún provecho.  
 
 **-Ataques a nivel de red:**  
 En primer lugar, se explica brevemente como funcionan las redes TCP_IP ya que todos los ataques explicados se basan en ellas.
 En este módulo se exponen cuatro tipos de ataques:
 - *Mac Flooding*: Consiste en agotar la tabla MAC de un dispositivo(switch) para provocar un envío a difusión.  
 - *Mac Spoofing*: Consiste en suplantar la MAC de un dispositivo dentro de una red para distintos fines(Ataques DOS, robar información...).  
 - *Man in the Middle*: Consiste en capturar la información intercambiada entre cliente y servidor ilegíticamente.  
 - *DNS Spoofing*: Consiste en crear tramas falsas para envenenar las resoluciones de consultas DNS.  
 
 **-Vulnerabilidades y Metasploit:**  
 En este módulo se explica que es una *vulnerabilidad y que tipos existen*, y como explotarlas con el framework *Metasploit*, donde se enseñan
 varios comandos propios de Metasplot y varias herramientas auxiliares como Msfpayload, Msfencode y Msfvenom que integra las dos anteriores.  
 
 **-Anonimato:**
 Se explica en que consiste el anonimato de cara a la ciberseguridad y de porque es tan importante. También se explica como funciona
 la red *TOR* y que usos se le puede dar.
 
 
 ##  Curso de Triage Informático
 
 **-Introducción:**  
 En este tema se tratan asuntos tales como los tipos de *malware* existentes y sus características, se habla de los procesos y de como analizarlos y las diferencias entre un *Hacker* y un *Cracker*.  
 
 **-Búsqueda de malware:**  
 En este módulo se tratan temas como los mitos que giran alrededor de el hacking y el malware, de los metadatos y de como analizarlos y del *análisis heurístico*.  
 
 **-Análisis de archivos ejecutables:**  
 El tema trata de entender las rutas de instalación y ejecución, para así sacar información relevante para estudiar el malware y tambien del analisis de recursos para poder dictaminar si nuestro dispositivo está afectado por algún tipo de malware.  
 
 **-Emails y phishing:**  
 En este apartado se estudian diferentes ejemplos de mails sospechosos y archivos infectados y de como lidiar con ellos a parte de una pequeña práctica sobre creación de máquinas virtuales con *VMware*
 
 
 
 
 
 
 
 
 
 
  
  
