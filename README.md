# TouchDesigner OSC Controller
A repository demonstrating OSC interaction between TouchDesigner and a mobile phone. In this case the gyroscope in the mobile phone is used to control the pitch and roll of a 3D object onscreen.

To use the TOE file you will need to download [TouchDesigner](https://derivative.ca/) by Derivative. This can be used freely for non-commercial projects and education. This example also uses the [GyrOSC](http://www.bitshapesoftware.com/instruments/gyrosc/) app to enable a mobile device to communicate with TouchDesigner over a local WiFi network. This is achieved using the Open Sound Control (OSC) protocol. To establish a connection the app requires the IP4 address of the target machine and a Port number. The default port for Touchdesigner is `10000`.
