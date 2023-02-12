# Tiny Reflow Controller
An all-in-one Arduino compatible reflow controller powered by ATmega328P (V2) or ATtiny1634R (V1). A reincarnation of the Reflow Oven Controller Shield that requires an external Arduino board like Arduino Uno based on user feedbacks over the years. Powered by the ATmega328P/ATtiny1634R coupled with the latest thermocouple sensor interface IC MAX31856 from Maxim, we managed to remove the need of an Arduino board and reduce the overall cost. We also use as much SMD parts in this revision to keep the cost low (manual soldering and left over residue cleaning is time consuming) and leaving only the terminal block and the LCD connector on through hole version. We also managed to streamline all components to run on 3.3V to further simplify the design. All you need is an external Solid State Relay (SSR) (rated accordingly to your oven), K type thermocouple (we recommend those with fiber glass or steel jacket), and an oven of course! You can now select to run a lead-free profile or leaded profile from the selection switch. V2 comes with 0.96" 128*64 OLED LCD to plot the real-time reflow curve and has a built-in serial-USB interface. V2 also has an optional transistor output drive fan if needed. 

## Fork Notes

I've modified the hardware to be mounted inside a box, keeping the same board size -- essentially just adding headers for buttons with a few more tweaks.

### Hardware

Changes in Rev A1 (based on "2v00 12-2018"):

  - Import/clean-up for Kicad 6
  - Removed reset button (no room), replaced with 2-pin header
  - Added 2-pin headers for buttons
  - Added extra 5V input on a 2-pin header
  - OLED footprint now through-hole
  - Resonator footprint changed to SMD5032-2P

### Firmware

tbd
