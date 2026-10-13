# Análisis Trafico con Wireshark
Estudio de análisis y trafico de un caso de redes usando Wireshark y una captura de trafico .pcap


## Estudio de caso

Usando la herramienta Wireshark se estudia y practica una Metodología de análisis de tráfico en una red, usando de practica una captura de tráfico .pcap proveniente de un virus de practica alojado en: https://www.malware-traffic-analysis.net/ 

el propósito del caso es comprender a mayor profundidad el análisis de tráfico y en uso de la herramienta Wireshark en propósito del estudio de la ciberseguridad y el hacking etico.

### Metodología
El proceso y metodología fue realizado en el entorno virtualizado VirtualBox usando una máquina virtual Kali Linux, con el propósito de mantener control y seguridad del equipo a la hora de realizar el analisis.

Primero se accede a internet por medio de Mozilla Firefox a la página donde esta hospedado el caso, se descarga un archivo de nombre 2024-04-09-Latrodectus-pcap-and-malware-dump-from-infection.zip que posee en su interior el archivo .pcap

Se decomprime el archivo .zip en la maquina virtual usando el comando: 
sudo unzip 2024-04-09-Latrodectus-pcap-and-malware-dump-from-infection.zip
Seguido con la contraseña del archivo, al tener descomprimido el archivo se utiliza el comando: 
sudo wireshark
Para acceder al entorno de Wireshark

Se abre el archivo .pcap y la ventana Conversations mediante el menú Statistics, con el propósito de verificar los dominios a los que se accedió anteriormente para verificar si se accedió o no a dominios extraños, haciendo este proceso se encuentra una irregularidad en el tráfico de un paquete, se usa un filtro mediante la interfaz grafica para analizar en el entorno base de Wireshark el registro.

