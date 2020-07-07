For u16 & u18 New version pool 2020

sudo apt-get update -y

sudo apt-get upgrade -y
______________________________________________________

dd if=/dev/zero of=/mnt/myswap.swap bs=1M count=4000

mkswap /mnt/myswap.swap

swapon /mnt/myswap.swap

nano /etc/fstab

paste this *************

/mnt/myswap.swap none swap sw 0 0

______________________________________________________


git clone https://github.com/xavatar/yiimp_install_scrypt.git

sudo apt -y install git

cd yiimp_install_scrypt/


______________________________________________________

git clone https://github.com/allforminers/installubuntu.git

cd installubuntu

sudo bash install.sh

cd ..

______________________________________________________










