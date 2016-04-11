# navio2

Some scripts and stuff to improve navio2 by http://www.emlid.com/shop/navio2/


# Automatic start of ardupilot on boot
Create a new file with
`sudo nano /etc/init.d/ardupilot`
and copy in the content from https://github.com/SamuelBrucksch/navio2/blob/master/ardupilot. Then run `sudo update-rc.d ardupilot start` and the autopilot will start at boot. Logfile is saved to `/home/pi/arduplane.log` 
