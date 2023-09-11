
# Getting an Iomega zip 100 parallel storage drive running again 


I had an old Iomage Zip 100 drive with a parallel interface.

This README documents the setup on an old Windows XP machine with a parallel port.

1. Connect the drive as shown below and powe up. My drive did not autodetect, so I completed the following steps.
2. On XP Desktop goto `Start` and rightclick on `My Computer` and select `Manage`
3. Select `Device Manager` and expand `Ports (COM & LPT)`
4. Right-click on `Printer Port(LPT1)` and select `Scan for hardware changes`

After completing these step my drive appeared.

TomGoBravo attempted the same steps with a similar setup and needed to open the LPT1 Properties and check `Enable legacy Plug and Play detection` in the `Port Settings` tab before `Scan for hardware changes`. His drive does not have AUTODETECT stamped above the rear left parallel port and has Model Number `Z100P2` printed above the DC power socket.

Importantly, I did not have to download any of the dodgy drivers offered on the internet.

I was pleasantly supprised that the data on the drives was fully intact after all these years.


![Connection to Drive](https://github.com/chseeling/iomegazip100/blob/master/IOMEGA_ZIP100_withCable.jpg)
