# ftdiflash for Trion
simple SPI flash programmer for use with Efinix Trion eval kits

Try something like: `xxd -r -p < outflow/t20_mipi_evk.hex > t20_mipi_evk.bin && ./ftdiflash t20_mipi_evk.bin`

This will program the attached SPI flash on your Efinix Trion T20 MIPI eval
kit, and reset the Trion.

This is a modified version of the Adafruit ftdiflash tool, from https://github.com/adafruit/ftdiflash
, which in turn is a modified version of the iceprog tool from the excellent Icestorm FPGA toolchain by Claire Wolf et al
https://github.com/YosysHQ/icestorm 
