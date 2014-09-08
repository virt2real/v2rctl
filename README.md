v2rctl
=======

Virt2real device control API.

Roadmap
-------
(*W* - working on, *v* - done, *x* - reject, *s* - wait for)

### Prototype phase
* [w] Working with video via gstreamer/gstd controled by REST/JSON-RPC via web UI

### 1st iteration 
* [s] System controm
  * [s] Kernel startup params
  * [s] Startup services and daemons
  * [s] Logs extract
  * [s] Reset & Shutdown
  * [s] Software control (install/remove/updare)
  * [s] Flash to NAND ROM  
  * [s] File manager & upload/download
  * [s] Runtime control (start/stop services and applications) 
  * [s] Device info 
  * [s] Usage statistics 
* [s] Network configuration and status
  * [s] Wi-Fi configuration (AP/Client modes)
  * [s] Ethernet & USB configuration
  * [s] 3G/LTE configuration
  * [s] DHCP client/server
  * [s] Routing and firewall
  * [s] Tunnels and VPN
* [s] Video/audio control
  * [s] Custom video presets
  * [s] Broadcasting types
  * [s] Client's support (Flash, VLC, QT) 
  * [s] Broadcasting services integration
  * [s] Camera configurations
* [s] I/O control
  * [s] USB devices
  * [s] GPIO operations
  * [s] I2C operations
  * [s] SPI operations
  * [s] PWM/PPM operations
  * [s] DAC/ADC operations
* [s] Common devices support
  * [s] Shields support 
  * [s] GPS/GLONASS support
  * [s] Additional data sources support

### Misc functions
* [s] Interactive shell
* [s] Autodeployment to device (one command) 
* [s] Autoremove
* [s] Trusted autoupdates
