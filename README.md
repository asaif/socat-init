ABOUT
=====

 socat-init is a samll Debian LSB init tool to manange the behaviour of socat daemon on Debian Gnu/Linux.

INSTALLATION
============
  
  Installtion steps are so easy just do the follwoing :
  
  1. Clone socat-init to your home directory

       $: git clone https://asaif@github.com/asaif/socat-init.git /home/$user

  2. Copy the files to the right path

        sudo cp -a /home/$user/socat-init/socat /etc/init.d/
        sudo cp -a /home/$user/socat-init/defaults/socat.conf /etc/defaults/

Now socat-init has been installed and is ready to be used.

Usage
=====
 You can use socat-init like any other init file by excuting socat tool and pass the desired action, for example:
 
    /etc/ini.d/socat start
 
 To see the help just execute the tool without any actions.

Cheers ;)