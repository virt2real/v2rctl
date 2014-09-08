v2rctl
=======

Virt2real device control API.

Roadmap
-------
(*w* - working on, *v* - done, *x* - reject)

### Prototype phase
* [w] Working with video via gstreamer/gstd controled by REST/JSON-RPC via web UI

### 1st iteration 
* [_] System controm
.* [_] Kernel startup params
.* [_] Startup services and daemons
.* [_] Logs extract
.* [_] Reset & Shutdown
.* [_] Software control (install/remove/updare)
.* [_] Flash to NAND ROM 
.* [_] File manager & upload/download
.* [_] Runtime control (start/stop services and applications) 
.* [_] Device info 
.* [_] Usage statistics 
* [_] Network configuration and status
.* [_] Wi-Fi configuration (AP/Client modes)
.* [_] Ethernet & USB configuration
.* [_] 3G/LTE configuration
.* [_] DHCP client/server
.* [_] Routing and firewall
.* [_] Tunnels and VPN
* [_] Video/audio control
.* [_] Custom video presets
.* [_] Broadcasting types
.* [_] Client's support (Flash, VLC, QT) 
.* [_] Broadcasting services integration
.* [_] Camera configurations
* [_] I/O control
.* [_] USB devices
.* [_] GPIO operations
.* [_] I2C operations
.* [_] SPI operations
.* [_] PWM/PPM operations
.* [_] DAC/ADC operations
* [_] Common devices support
.* [_] Shields support
.* [_] GPS/GLONASS support
.* [_] Additional data sources support

### Misc functions
* [_] Interactive shell
* [_] Autodeployment to device (one command) 
* [_] Autoremove
* [_] Trusted autoupdates
