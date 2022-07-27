# One-Button-On-OFF-Arduino-system

The Arduino in this circuit can turn itself off by changing the state of its pin.
The circuit uses p-mosfet and bjt trnasistors to function as a latch.
the button turns the bjt On, and the bjt allows the current to flow through the source of the mosfet to the drain.Thus, the Arduino turns On.
the code of the Arduino sets pin 8 to HIGH to keep the bjt On.Therefore, the power source will continue to power the arduino through the mosfet.
When the code changes the status of the pin to LOW, the bjt will turn off. Thus, the channel between the source and drain is blocked and the arduino turns Off.
