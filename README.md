# Arduino-Python-Serial-Bluetooth-Communication
Tutorial on how to communicate between Arduino and Python wirelessly through serial bluetooth communication.

Initially, I was trying to use Python's PyBluez library with Arduino's Software Serial library to send data between Arduino and Python through bluetooth, according to the following website:

https://create.arduino.cc/projecthub/nhuberfeely/remote-bluetooth-light-control-with-python-8308fc

The Tkinter GUI is interesting and the bluetooth pairing is done on python. Neat! But I couldn't get it to work. Instead, I manually paired the Arduino Bluetooth HC-05 module with my Windows 10 laptop according to any of the following tutorials (the code for pairing is 1234):

https://www.collideabq.com/2016/04/28/bluetooth-serial-connection-with-windows-10/

https://www.freetronics.com.au/pages/bluetooth-pairing-guide#.Xr6BF2hKiUk

Then, the Arduino and Python code was sourced from here:

https://github.com/LessonStudio/Arduino_Bluetooth

https://create.arduino.cc/projecthub/millerman4487/view-serial-monitor-over-bluetooth-fbb0e5?fbclid=IwAR0S18LQikipV4Bz-7_XL-MoJVZcsCjW8dqWhOz3LE9lG1cBtPUHPL-6dtE

https://gist.github.com/geoom/99d1407992364c3f9553?fbclid=IwAR0ivbRToUozxZTRUn1FfOukW_DGm1tKjVq-boVImS4fD-8us3hZgyNGtsU

