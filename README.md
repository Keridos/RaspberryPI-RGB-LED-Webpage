# RaspberryPI-RGB-LED-Webpage
A script from this youtube user patched to work well with HTML5 and to display properly on Firefox: https://www.youtube.com/watch?v=DcGSXTMwzJ4

Follow this tutorials for LED wiring : http://mitchtech.net/raspberry-pi-pwm-rgb-led-strip/

Copy all files to the Pi in the right folder

Make sure the python files in the cgi-bin folder have the executable flag (sudo chmod +x *.py)

Set the pin number you use in the \usr\lib\cgi-bin\LED.py file.  default is 4, 17 and 18.

Make sure you have php, apache and the build requirements for pi-blaster installed (commands for debian):
```
sudo apt-get update
sudo apt-get install apache2 php5 libapache2-mod-php5 autoconf
```

Install pi-blaster from : https://github.com/sarfata/pi-blaster/ :
```
git clone https://github.com/sarfata/pi-blaster.git
cd pi-blaster
./autogen.sh
./configure
make
sudo make install
```

Open a browser on http://Raspberrypi_Ip_Address

Enjoy ;)

]SaRgE[ and Keridos
