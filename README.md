# tea5767-esp8266-nodemcu
Just simple small test to see if i2c works on esp8266 with nodemcu,

Lua script implements i2c interface from esp8266 to tea5767, with webpage to change frequency.

All you need is: 
-3.3V usb2ttl module to burn nodemcu and upload script,

-tea5767 module,

-any esp8266 module (esp-01 works just fine),

And software:

-Nodemcu firmware,

-esptool,

-esptool.py,

-luatool.py,

If you wire and burn everithing together you get simple wifi enabled fm radio. 

For me this was just simple helo world for lua and html, so don't expect any futher improvments from me in near future. 
If anyone is interested in further development this is just top of the todo list: 
sw todo:

-better user interface,

-search function,

-memmory for channels,

-...

sw & hw todo:

-manual control(gpio buttons),

-oled display,

-volume control,

-...

For any spare bitcoin change I might consider adding aditional functions as well: 
1MaGphnuiMjywjQPKHKF239wzcef4KpNxX 


Copyright (C) 2015  Uros Golob na1piratgmaildotcom


    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
