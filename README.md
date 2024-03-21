# raspberrypi-motor-HAT

[RaspBerryPi Motor HAT Adafruit Learn](https://learn.adafruit.com/adafruit-dc-and-stepper-motor-hat-for-raspberry-pi)

## Python Installation of MotorKit Library
You'll need to install the Adafruit_Blinka library that provides the CircuitPython support in Python. This will require enabling I2C on your Raspberry Pi and verifying you are running Python 3. Since Linux changes often, please visit the CircuitPython on Linux guide to get your computer ready!

Once that's done, from your command line run the following command:

sudo pip3 install adafruit-circuitpython-motorkit
If your default Python is version 3 you may need to run pip instead. Just make sure you aren't trying to use CircuitPython on Python 2.x, it isn't supported!

This will install the Adafruit CircuitPython MotorKit library along with the necessary dependencies.
