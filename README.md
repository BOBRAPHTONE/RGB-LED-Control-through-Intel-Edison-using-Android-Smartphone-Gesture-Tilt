# RGB LED Control through Intel Edison using Android Smartphone Gesture (Tilt)
Controlling an RGB LED through Intel Edison using Android smartphone gesture (Tilt)

The idea is to introduce smartphone with Intel Edison to trigger/control an event using sensors on smartphone. Most Android-powered devices have built-in sensors that measure motion, orientation, and various environmental conditions. These sensors are capable of providing raw data with high precision and accuracy.

By tilting the phone around Y-axis (Roll), control the color variations of an RGB LED which is connected to Edison.

## Sofware Tools
* Android Studio

## Hardware
* [Intel Edison](http://www.intel.com/content/www/us/en/do-it-yourself/edison.html)
* [RGB LED](http://www.ebay.in/itm/8mm-Diffused-Round-RGB-LED-Diode-Common-Anode-Super-Bright-4-Legs-10-Pcs-Per-Lot-/171983997852?_trksid=p2054897.l4275)
* Android Smartphone (Should contain Accelerometer and Magnetometer)
* [220 Ohm Resistor - 3](http://www.amazon.com/E-Projects-Resistors-Watt-220R-Pieces/dp/B00B5LNEF6)

## Software
* Bluetooth-SPP Python wrapper
* PyBluez

The above two application packages are Edison specific. To install and run the program, please follow this link.

## Credits
On Edison, the program was written by [Kiran Hegde](http://github.com/kiranmadansar) (Email: kiranmadansar@gmail.com)

