# FT232_USB_to_TTL_Converter
I designed the TTL converter myself for use in electronic circuits and projects. 
It is a project that I realized with the spnsorship of PCBway.
Again, I will share the production files publicly on the PCBway web site. If you want to order, you can access from the link below.
https://www.pcbway.com/project/shareproject/FT232_USB_to_TTL_Converter.html
![alt text](https://github.com/caliskanali/FT232_USB_to_TTL_Converter/blob/master/USBtoRS232.jpg)
![alt text](https://github.com/caliskanali/FT232_USB_to_TTL_Converter/blob/master/USBtoRS232_bottom.jpg)

To do this, I used the FT232RL integrated by the FTDI company and made some changes from the reference scheme.
# SCHEMATIC BLOG DIAGRAM
![alt text](https://github.com/caliskanali/FT232_USB_to_TTL_Converter/blob/master/Schema_blog.jpg)
The first is to adjust the IO voltage. By adding 2 regulators to the diagram (3), we have switchable IO voltage of 1.8V - 3.3V and 5V. (4)
RX - TX data LEDs added. (5) On the output port, I added a TVS diode for external ESD protection to the Tx and Rx pins (6).
