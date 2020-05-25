Instalar ANSIBLE:
https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html
 
Instalar PIP python:
https://pip.pypa.io/en/stable/installing/

Instalar ferramente de conexão paramiko:
http://www.paramiko.org/installing.html

Após instalação das ferramentas acima, existe alguns ajustes a serem realizados no qual precisei adaptar devido a minha infraestrutura interna.

Arquivo ANSIBLE.CFG, alterar o parametro host_key_checking = False

# uncomment this to disable SSH key host checking
host_key_checking = False
