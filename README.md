# emily-usv
Data and parameters of an EMILY USV


**Ardurover parameters file**: `emily_ardurover.params`

# Configuring Autonomous EMILY USV

This manual describes how to add autonomous capability to a standard [EMILY USV](https://www.emilyrobot.com/). This configuration has been called “Smart EMILY”. It uses a [Pixhawk Mini](https://docs.px4.io/v1.9.0/en/flight_controller/pixhawk_mini.html) flight controller with [ArduRover](https://ardupilot.org/rover/) autopilot software system. This text is a work-in-progress, since we are continually testing and improving the configuration. Follow-up documents will describe how to integrate various sensors and additional capabilities. Here, the basic setup required for waypoint-following autonomy is presented.

## Required materials

**Vehicle**

- [E.M.I.L.Y. ERS](https://www.emilyrobot.com/)

**Autopilot**

- [Pixhawk Mini](https://docs.px4.io/v1.9.0/en/flight_controller/pixhawk_mini.html)
- [Quad Power Distribution board](https://docs.px4.io/v1.9.0/en/flight_controller/pixhawk_mini.html)
- [Ublox GPS + compass module](https://ardupilot.org/copter/docs/common-installing-3dr-ublox-gps-compass-module.html)
- [SiK radio telemetry module](https://ardupilot.org/copter/docs/common-sik-telemetry-radio.html) **Note, will replace with long-range RFD900**
- [Spektrum DSMX receiver](https://www.horizonhobby.com/product/dsmx-remote-receiver/SPM9645.html)

**Ground control station**

- Laptop running [QGroundControl](http://qgroundcontrol.com/)
- [SiK radio telemetry module](https://ardupilot.org/copter/docs/common-sik-telemetry-radio.html) **Note, will replace with long-range RFD900**
- [Logitech Dual-Action gamepad](https://www.amazon.com/Logitech-Dual-Action-Game-Pad/dp/B0000ALFCI)

**Radio control transmitter**

- [Spektrum DX8](https://www.spektrumrc.com/Products/Default.aspx?ProdID=SPMR8000)

## Hardware integration

Section coming soon? 

1. I need to study the wiring, since I did not do this part
2. Since [CRASAR](http://crasar.org/) did this, I’m not just assuming I can share it. That said, you can figure it out from the [Pixhawk Mini wiring quick start](https://madennis.gitbooks.io/px4user/content/en/assembly/quick_start_pixhawk_mini.html).
