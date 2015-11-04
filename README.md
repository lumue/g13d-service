# installing [g13d](https://github.com/ecraven/g13) as a systemd service

scripts to checkout, build, install and run [g13d](https://github.com/ecraven/g13) as a systemd service. tested with debian sid.

the steps that are executed are explained [here](http://lumue.github.io/2015/11/03/using-logitech-g13-on-debian-sid.html)


## build and install

to build and install use:

    ./build.sh && sudo ./install.sh


## starting and stopping the service

start service
 
    sudo systemctl start g13d-service
    
start service
  
    sudo systemctl stop g13d-service
     