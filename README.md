v2r_ctl
=======

Virt2real device control API.

Roadmap
=======

(w - working on, v - done, x - reject)

* Prototype phase
** [w] Working with video via gstreamer/gstd controled by REST/JSON-RPC via web UI

* 1st iteration 
** [ ] System controm
*** [ ] Kernel startup params
*** [ ] Startup services and daemons
*** [ ] Logging extract
*** [ ] Reset & Shutdown
*** [ ] Software control (install/remove/updare)
*** [ ] Flash to NAND ROM 
*** [ ] File manager & upload/download
*** [ ] Runtime control (start/stop services and applications) 
*** [ ] Device info 
*** [ ] Usage statistics 
** [ ] Network configuration and status
*** [ ] Wi-Fi configuration (AP/Client modes)
*** [ ] Ethernet & USB configuration
*** [ ] 3G/LTE configuration
*** [ ] DHCP client/server
*** [ ] Routing and firewall
*** [ ] Tunnels and VPN
** [ ] Video/audio control
*** [ ] Custom video presets
*** [ ] Broadcasting types
*** [ ] Client's support (Flash, VLC, QT) 
*** [ ] Broadcasting services integration
*** [ ] Camera configurations
** [ ] I/O control
*** [ ] USB devices
*** [ ] GPIO operations
*** [ ] I2C operations
*** [ ] SPI operations
*** [ ] PWM/PPM operations
*** [ ] DAC/ADC operations
** [ ] Common devices support
*** [ ] Shields support
*** [ ] GPS/GLONASS support
*** [ ] Additional data sources support

* Misc functions
** [ ] Interactive shell
** [ ] Autodeployment to device (one command) 
** [ ] Autoremove
** [ ] Trusted autoupdates
