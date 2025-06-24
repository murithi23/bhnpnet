Description

BNP Net tool is a light weight python script that enables":
remote command execution
file uploads
ineractive command shell
TCP client/server communication


Features

bind/listen mode(-l) his is o accept incoming connections
command execution -e run a specific command
ineeractive shell -c spawn command shell
file upload -u uploads files to the target
raw tcp client sends data from stdin

Insallation
only requirements are python 3

download he script from he repository

git clone https://github.com/murithi23/bhnpnet.git
cd bhpnet

Usage 
To start a listener on port 55 with a command shell
     python bpnet.py - <targe_ip> -p <port> -l -c

To execue a command remoel     
     python bpnet.py - <target_ip> -p <target_port> -l -e "ls -la"

To upload a file 
   python bhnpnet.py - <target_ip> -p <target_port> -l -u /path/to/upload 

basic command shell
server
 python bhnpnet.py - <target_ip> -p  4444 -l -c

client
nc <server_ip> 4444



!!!!!secure noice!!!!!
the script is for educational and research purposes only 
use carefully and ethically





      
