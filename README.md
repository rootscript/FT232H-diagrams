# FT232H-diagrams.
Just some working diagrams to help with setting up circuits with the FT232H breakout board.  I've read so any tutorials that would greatly benefit from some clear diagrams with some concise notes (Similar to 'Quick Setup Guides & revision cards etc... A picture speaks a thousand words).

I'm using the FT232H board with Mac OS X 10.10.4 and the system version of Python which is Python 2.7.6.

The FT232H board has GPIO, SPI, and I2C connections, and I will be documenting my attempts to connect to these types of devices.

####SPI:
- Connect to `NeoPixels` via `SPI` (completed, but still need to document & create diagrams/photos).

####I2C:
- Connect to `PCA9685` via `I2C` (in progress).
[to Control PWM, servos, etc...]
- Connect to `DRV2605L` via `I2C` (planned).
[Haptic Motor driver]
- Connect to `TB6612` via `PWM` (planned, need to connect to `PCA9685` board first to get `PWM` to control the `TB6612`)
[to Control stepper motors]

####Other useful components (that are often overlooked, but needed by beginners):
- Connect to `74AHCT125N` Quad Level-Shifter. (completed, but still need to document & create diagrams/photos).
- Connect to `4.7K Ohm 1/4 Watt Resistor`. (completed, but still need to document & create diagrams/photos).
- MQTT API Python IO. (planned) aiming to setup web based widgets (Color pickers, locations on Google maps etc...) to control/monitor devices.

I am aiming to get a full list of devices connected to the FT232H, and would like to document how to achieve that, so that people who are new to this subject area will have a starting point with many example to compare.
Having more that one example is vital, as it is only through comparison that new people will be able to start to understand, and be more comfortable experimenting with other new devices.

## Example Diagrams:
![Image](/_readyForEmbedding/FT232H-pullup-resistor-01%5B728x569%5D.jpg?raw=true)

## Related written documents:
{% gist 6e69c1366a2af550b577 %}
{% gist 6e69c1366a2af550b577 pca9685-md %}
