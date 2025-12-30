# cybersecurity-basic-projects
Basic cybersecurity projects focused on log analysis, virtual machines and system hardening. 
Proyectos de ciberseguridad basicos enfocados en analisis de Logs, maquinas virtuales y hardening básico.
# Cybersecurity Basic Projects
This repository contains basic academic projects developed as part of my cybersecurity training
Este repeositorio contiene prácticas básicas qu he estado realizando en los primeros semestres en mi carrera

# Project 1: Linux Log Analysis
- Analysis of authentication logs (auth.log)
- Identification of failed login attempts
- Use of basic Linux commands (journalctl, grep)
 Commands used:
sudo journalctl -p err -b
 sudo journalctl --since "today" -u ssh

<img width="646" height="514" alt="image" src="https://github.com/user-attachments/assets/b61cf0a9-c98a-42c3-aaca-9e29c6ff0bdd" />

# Result
The analysis allowed the identification of system errors and SSH authentication activity,
helping to understand how logs can be used to detect potential security issues.
Estos comandos permiten identificar erroes de autenticación SSH recientes con el fin de detectar amenazas. 

# Project 2: Virtual Machines for Security Testing
- Configuration of Kali Linux in VirtualBox
- Basic network commands
- Safe testing environment
 Commands used:
ip a
nmap localhost

<img width="647" height="511" alt="image" src="https://github.com/user-attachments/assets/b67aaec7-632b-4979-9202-5b640b1c5a54" />

#Result
The network interface and IP address of the virtual machine were identified.
A local scan was performed using Nmap, confirming that the host is active and that
all TCP ports are closed, which indicates a basic secure state in the test environment.

Con estos comandos se puede identificar la dirreción IP de mi maquina virtual, se escanea usando Nmap y se confima si el host está activo

# Project 3: Basic System Hardening
- System updates
- User and permission review
- Service analysis
Commands used:
sudo apt update && sudo apt upgrade
sudo systemctl list-units --type=service

<img width="642" height="464" alt="image" src="https://github.com/user-attachments/assets/803aa071-1785-4ad9-96f8-80658a9adea6" />

#Result
Active system services were identified and analyzed to understand which processes
are running by default. This helps reduce the attack surface by identifying
unnecessary services in a Linux environment.
Servicios activos fueron identificados y analizados, nos ayuda a reducir ataques al identificar servicios inecesarios en Linux. 

# Author
Andrea Mendez Coox  
Cybersecurity Student

