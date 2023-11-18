# Ox64-uart
Ox64-uart allows a Pico / RP2040 to be used as two UART bridges. By default these are set so that UART0 tx is on GPIO4, UART0 rx is on GPIO5, UART1 tx is on GPIO12, and UART1 rx is on GPIO13.  These can be changed by modifying picoprobe_config.h and re-building.


Ox64-uart is derived from [Picoprobe](https://github.com/raspberrypi/picoprobe), which has documentation  in the [Pico Getting Started Guide](https://datasheets.raspberrypi.com/pico/getting-started-with-pico.pdf). See "Appendix A: Using Picoprobe".
