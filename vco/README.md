# VCO

![VCA](preview.png)

The VCO consists of a simple NE555 circuit that is able to modulate the frequency and the pulse width of a square wave via a reference voltage. The output is connected to a simple binary counter to compensate the varying duty-cycle. As a nice side effect you can get different octaves of the signal from the different counter outputs. Additionately you can use the reset input of the counter and/or the NE555 to create a sync effect.

The impedance of the cv input is only ~5kOhm. It's best to use an impedance converter on the input.
