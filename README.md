[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/O5O4AKQ37)

# SmartRV AIO
**A ESP32 based smart home control board for a Camper/RV**

All feature requests are tracked in the GitHub issue tracker. 
[Feature Requests](https://github.com/RoBro92/feature-requests/issues)

This AIO board is planned to be able to work standalone or as part of a connected smart home network within a camper or RV. It will be designed based on suggestions from the community. As technology advances many are looking to automate tasks in day to day life, your recreational vehicle should be no different. Many existing monitoring systems are generally either very dated, or not very smart. This board will facilitate an all in one monitoring and control hub. 

The module has been kept as compact as possible and allows for a direct connection to 12v or 24v vehicle systems. 

**If you want to support the development you can purchase this board as a DIY kit or assembled from my Ko-Fi Shop [SmartRV Shop](https://ko-fi.com/smartrv/shop)**

## **I have developed two seperate versions of this module**

[AIO1 is THT and is suitable for at home soldering](#aio1)

[AIO2 is SMD and is designed to be assembled by a PCB manufacturer](#aio2)

###AIO1

# **THT Version 0.1**
This is the pre production initial design files with planned features and initial designs.


# **Features**
- [x] - ESP32 Microcontroller
- [x] - Individually controlled relays
- [x] - Input buttons 
- [x] - Tank temperature inputs
- [x] - Tank level inputs
- [x] - Auxilliary temperature & humidity input
- [x] - Spotlights/LED control & dimming
- [x] - RJ45 Output to Nextion Display
- [x] - Relay 1&2 are 12v direct supply for low current device 

# **Upcoming Changes**

- [ ] - RS485 serial connection
- [ ] - Bluetooth App
- [ ] - Bluetooth connection to external modules(such as Water tank module)
- [ ] - House battery voltage
- [ ] - Main battery voltage
- [ ] - On board programming
- [ ] - MQTT integration
- [ ] - Diesel heater control 

# **Images**

<table>
  <tr>
    <td>Schematic</td>
     <td>PCB Layout</td>
  </tr>
  <tr>
    <td><img src="AIO1/Images/Schematic.jpg" height=480></td>
    <td><img src="AIO1/Images/Pcblayout.jpg" height=480></td>
  </tr>
 </table>

# **WARNING**
This board does not have any fuse protection as such this must be provided externally.


###AIO2

# **SMD Version 0.1**
This is the pre production SMD initial design files with planned features and initial designs.


# **Features**
- [x] - ESP32 Microcontroller
- [x] - Individually controlled relays
- [x] - Input buttons 
- [x] - Tank temperature inputs
- [x] - Tank level inputs
- [x] - Auxilliary temperature & humidity input


# **Upcoming Changes**

- [ ] - RS485 serial connection
- [ ] - Bluetooth App
- [ ] - Bluetooth connection to external modules(such as Water tank module)
- [ ] - House battery voltage
- [ ] - Main battery voltage
- [ ] - On board programming
- [ ] - MQTT integration
- [ ] - Diesel heater control 
- [ ] - RJ45 Output to Nextion Display
- [ ] - Spotlights/LED control & dimming
- [ ] - Relay 1&2 are 12v direct supply for low current device 

# **Images**

<table>
  <tr>
    <td>Schematic</td>
     <td>PCB Layout</td>
  </tr>
  <tr>
    <td><img src="AIO2/Images/schematic.jpg" height=480></td>
    <td><img src="AIO1/Images/Pcblayout.jpg" height=480></td>
  </tr>
 </table>

# **WARNING**
This board does not have any fuse protection as such this must be provided externally.
