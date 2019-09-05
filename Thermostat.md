# Programmable Thermostat

## The Thermostat Program has two variables

1. Room temperature
2. Desired temperature

## Turn on the Micro Bit

On start up the **Micro Bit** sets the desired temperature to 22 deg C and begins displaying the room temperature.

The program compares the room temperature with the desired temperature.

If the room and desired temperatures are the same the Micro Bit continues to display the room temperature. It also sets pins 1 and 2 to low.

If the room temperature is lower than the desired temperature, the **Mirco Bit** will display an "*H*" for heat and the room temperature alternately. It also sets pin 0 to high to turn on the furnace and pin 1 to low.

If the room temperature is higher than the desired temperature, the **Mirco Bit** will display a "*C*" for cool and the room temperature alternately. It also sets pin 1 to high to turn on the air conditioner and pin 0 to low.

## Changing the desired temperature.
Pressing the **A button** will *increase the desired temperature*. When the A button is pressed the **Micro Bit** will increase the desired temperature one degree then display the desired temperature. This is repeated each time the A button is pressed.

When the **B button** is pressed the same thing happens except the *desired temperature is decreased*.  

To *display the desired temperature*, press the **A and B buttons** at the same time.
