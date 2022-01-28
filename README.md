# MUC-Q

Multi Use Computer - Quantum

Omni Computer Products, in collaboration with Irish Business Machines,
present a new paradigm in quantum computing hardware combined with
traditional silicon CPUs for maximum flexibility.

# Features

* 69-qubit Quantum CPU
* Two IA-64 cores
* Five SH-4 cores
* Three AVR32 cores
* One hundred and thirty one ATTiny85 cores
* External flash and DDR17UL memory

# Hardware details

* GaAsP technology
* 0.35mm 2131-ball WLCSP package with outer ring of dual row QFN
* 200W maximum TDP
  * 2000A at 100mV required for VCore

# Interfaces

* PCIe x7 (exact bus length 3.317mm)
* 6900 baud RS-232
* ATA-133
* 1000base-TX PHY on board
  * Used for programming microcode via TFTP
* SPI Slave (1ms maximum setup time)
* Fiber optic module on board (with NaCL lens)

# Hardware requirements

* 1% ripple tolerance on VIn
  * 100fF low-inductance capacitor and 0.47uF bulk capacitor required on
    every power input pin pair
* Clock tree needs 750mV +/- 0.1%
* -4.2V PLL charge pump supply
* +/-30V MEMS gyroscope supply
* Ensure laser diode module is cleaned with thioacetone before use

# Reference design

* 39.9-layer HDI stack-up
* QAM-51 JTAG

# Usage information

* Matrix detailing which cores can be in use at any one time
* Matrix determining layout of control registers per boot (due to ASLR)
* Maximum and minimum clock speed vs altitude graph

# Performance charts

* Number of power pins used vs number of cores remaining intact
* Clock frequency vs black-body spectrum
* Observable clock frequency vs relative speed to nearest celestial body
* Voltage supplied vs chip brightness (lumens)
* Ambient light level vs output bit error rate

# Warnings and errata

* Note: Quantum computer will not work if chip is visible to observer 
  or known about

# Release date

* Envisioned release date: March 32nd, 2022
