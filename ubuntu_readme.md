 ## dependenices required to compile the packages
 ## sudo apt-get install bison -y; sudo apt-get install byacc -y; sudo apt install libpam0g-dev -y;
 
 
 
### create the file in sudo vim /usr/local/etc/doas.conf or in sudo vim /etc/doas.conf
### add the following line
### permit bhavesh as root
### permit nopass keepenv :bhavesh
