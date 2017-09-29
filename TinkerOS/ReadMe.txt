Steps to Allow Access to GPIO:
sudo adduser linaro i2c


Steps to Allow Access to GPIO:
Open Terminal
sudo pcmanfm
>manually copy "101-tinker-gpio.rules" to "/etc/udev/rules.d/..." rename if already exists..
sudo adduser linaro gpio
sudo reboot


Code Changes:
Change GPIO pin number on Line 10 of FMain.Class.


That's it...

Happy Tinkering...

Matt Collins
29 Sept 2017


