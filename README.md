# Nmap-automation-Portscanner

This is a Python script that automates a port scan using the Nmap library. The code begins by importing the Nmap library and creating a port scanner object. 

The user is then prompted to enter an IP address, followed by a prompt to select from one of three types of scans. The script then checks that the response is valid and prints the current version of Nmap. 

The scan is then run with the specified IP address and port range, using the scan type specified by the user. Finally, the script checks the scan status, prints all protocols, and prints out the list of open ports.

This code is a python script that utilizes the nmap library to automate the task of running a port scan. It is written in the python programming language and uses the nmap library to facilitate network scanning.

The code begins by importing the nmap library. This provides access to the functions and classes that are necessary to perform a port scan. It then prints a welcoming message and prompts the user for an IP address to scan. It then prompts the user for a type of scan to run. 
The user can choose from three options: SYN ACK Scan, UDP Scan, or Comprehensive Scan. It then prints the IP address and selected scan type, as well as the version of nmap being used. 

The code then performs the actual port scan using the nmap library. It uses the scan() function, which takes three parameters: the IP address to scan, the port range to scan (1-1024 in this case), and the scan type (SYN ACK Scan, UDP Scan, or Comprehensive Scan). 
If the scan is successful, it prints the scanner status (whether the target is up or down) and all the protocols used, as well as a list of all the open ports. 

The code finishes by printing the scanner status. If the scan was successful, it will print the status of the target (up or down). If the scan was unsuccessful, it will print the status of the target (down). 
This code is a simple example of how to use the nmap library to automate the task of port scanning. It is a useful tool for network administrators and security professionals who need to quickly identify open ports on a network. It can also be used to help diagnose network issues or detect malicious activity.

# Wath I learn in the process

This project has helped to strengthen my Python coding abilities.

Consolidate my knowledge about NMAP portscanner and the different types of scanning it can perform.

Create an Automation in Python to simplify the use of NMAP and increase the efficiency
