## README #
# xtreamui_mirror

This is an installation mirror for xtream ui software.

### How do I install? ###

update your ubuntu first, then install panel  
  
* sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get install software-properties-common libxslt1-dev libcurl3 libgeoip-dev python -y;  
* rm install.py; wget https://github.com/dOC4eVER/ubuntu18.04/raw/master/install.py; 
* sudo python install.py  
  
If you want to install main server with admin panel, choose MAIN.  
If you want to install load balance on additional servers, add a server to panel in manage servers page, then run script and proceed with LB option.  

### note,
i forked this install.py is from https://github.com/emre1393/
