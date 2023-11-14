# Description of how you encoded seconds into lights.
I connected 6 LEDs on the breadboard and made them shine one by one, each lasting for 10 seconds. 
I introduced a new variable `sec = millis()/1000` to represent seconds. I attempted to control their brightness using numeric values. However, I encountered an issue with the `digitalWrite` function, which turns each LED on or off based on the corresponding `pXv` value. If the value is positive, the LED turns on; otherwise, it turns off. 
So, I decided to use `if` statements to determine the brightness of LEDs, dividing one minute into six parts and redefining their brightness every ten seconds.

# A schematic drawing of your circuit.
I connected the six LED lights in parallel, and each circuit is completed by Arduino + 100-ohm resistor + LED. 
Here is my circuit diagram:
![GhpbGX.jpg](https://imgpile.com/images/GhpbGX.jpg)

[Actual Circuit Photo]
![GhpGQg.jpg](https://imgpile.com/images/GhpGQg.jpg)