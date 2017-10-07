Steps to Allow Access to i2c:
sudo apt-get install i2c-tools
sudo adduser linaro i2c


Steps to Allow Access to GPIO:
Open Terminal
sudo pcmanfm
>manually copy "101-tinker-gpio.rules" to "/etc/udev/rules.d/..." rename if already exists..
sudo groupadd gpio
sudo adduser linaro gpio
sudo reboot


That's it...

Happy Tinkering...

Matt Collins
7 Oct 2017


