# docker_wordpress_rpi
Install Wordpress on Raspberry Pi (64-bit OS)

I was not able to install mysql on my Raspberry Pi 4 running Kali (64-bit).
The solution is to just use mariadb instead.
Everything else is the same...supposed to be 100% compatible with mysql

Copy the code to a file named docker-compose.yml and make sure this file is in the same directory that you initiate a "docker-compose up -d" from

# To get it to install and run:
mkdir wordpress
cd wordpress
!!!!make sure your docker-compose.yml file is here!!!!
sudo docker-compose up -d



# To Tear Down
$ sudo docker-compose down --volumes
