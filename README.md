Portable loads such as video cameras, halogen flood lights, electrical irons, hand drillers, grinders, and cutters are powered by connecting long 2- or 3-core cables to the mains plug. Due to prolonged usage, the power cord wires are subjected to mechanical strain and stress, which can lead to internal snapping of wires at any point. In such a case most people go for replacing the core/cable, as finding the exact location of a broken wire is difficult. The circuit presented here can easily and quickly detect a broken/faulty wire and its breakage point in 1-core, 2-core, and 3-core cables without physically disturbing wires and this circuit is built using CD4069 Hex inverter.Gates N3 and N4 are used as a pulse generator that oscillates at around 1000 Hz in audio range. The frequency is determined by timing components comprising resistors R3 and R4, and capacitor C1. Gates N1 and N2 are used to sense the presence of 230V AC field around the live wire and buffer weak AC voltage picked from the test probe. The voltage at output pin 10 of gate N2 can enable or inhibit the oscillator circuit. When the test probe is away from any high-voltage AC field, output pin 10 of gate N2 remains low. As a result, diode D3 conducts and inhibits the oscillator circuit from oscillating. Simultaneously, the output of gate N3 at pin 6 goes ‘low’ to cut off transistor T1. As a result, LED1 goes off. When the test probe is moved closer to 230V AC, 50Hz mains live wire, during every positive half-cycle, output pin 10 of gate N2 goes high. A 3V DC supply is sufficient for powering the whole circuit. Alternatively, one may use two 1.5V R6- or AA-type batteries. Using this gadget, one can also quickly detect fused small filament bulbs in serial loops powered by 230V AC mains. 
Then connect 230V AC mains live wire at one end of the faulty wire, leaving the other end free. Connect neutral terminal of the mains AC to the remaining wires at one end. However, if any of the remaining wires is also found to be faulty, then both ends of these wires are connected to neutral. For single-wire testing, connecting neutral only to the live wire at one end is sufficient to detect the breakage point. To detect the breakage point, turn on switch S1 and slowly move the test probe closer to the faulty wire, beginning with the input point of the live wire and proceeding towards its other end. LED1 starts glowing during the presence of AC voltage in faulty wire. When the breakage point is reached, LED1 immediately extinguishes due to the non-availability of mains AC voltage. During testing avoid any strong electric field close to the circuit to avoid false detection.

Tragbare Lasten wie Videokameras, Halogenfluter, elektrische Bügeleisen, Handbohrer, Schleifmaschinen und Schneidgeräte werden durch das Anschließen langer 2- oder 3-adriger Kabel an den Netzstecker mit Strom versorgt.


