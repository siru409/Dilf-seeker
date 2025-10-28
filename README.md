# Dilf-seeker
A near field multi beam ultra wideband fmcw radar detector using a novel near field focussed rotman lens

# to do maybe Hardware:
1. RX input limiter (strong RF sources close to dish)
2. FPGA compute port (if 4096 point FFT is not sufficient)


# to understand:
1: LOW if image rejection (ADL5380ACPZ-R7)

# to do Hardware:
 1. RF traces ??
2. RX Chain finish
3. TX pll dimensions
4. MCU peripherals
5. Confirm charge pump circuit

# board tests:
0. does Balun Transformer output match IQ demod input impedance (yes)
1. Coupled TX IQ demod input <13dbm?
2. Test supplies first, only then add 0 ohm resistors to power sensitive components


# Design choices to make

1. Buttler matrix vs rotman lens -> rotman lense (potentially more array ports within reasonable space)
2. Vivaldi vs Horn Array-> Vivaldi array -> can be implemented in single PCB
3. 2 elliptical dishes vs combined rxtx vs TX dish + 8 fixed RX horns
4. Inductitity values for RX/TX inline buffers


# User manual

# simulation results

# Filtering
