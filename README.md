Portable loads such as video cameras, halogen flood lights, electrical irons, hand drillers, grinders, and cutters are powered by connecting long 2- or 3-core cables to the mains plug. Due to prolonged usage, the power cord wires are subjected to mechanical strain and stress, which can lead to internal snapping of wires at any point. In such a case most people go for replacing the core/cable, as finding the exact location of a broken wire is difficult. The circuit presented here can easily and quickly detect a broken/faulty wire and its breakage point in 1-core, 2-core, and 3-core cables without physically disturbing wires and this circuit is built using CD4069 Hex inverter.Gates N3 and N4 are used as a pulse generator that oscillates at around 1000 Hz in audio range. The frequency is determined by timing components comprising resistors R3 and R4, and capacitor C1. Gates N1 and N2 are used to sense the presence of 230V AC field around the live wire and buffer weak AC voltage picked from the test probe. The voltage at output pin 10 of gate N2 can enable or inhibit the oscillator circuit. When the test probe is away from any high-voltage AC field, output pin 10 of gate N2 remains low. As a result, diode D3 conducts and inhibits the oscillator circuit from oscillating. Simultaneously, the output of gate N3 at pin 6 goes ‘low’ to cut off transistor T1. As a result, LED1 goes off. When the test probe is moved closer to 230V AC, 50Hz mains live wire, during every positive half-cycle, output pin 10 of gate N2 goes high. 

Tragbare Verbraucher wie Videokameras, Halogen-Flutlichter, Bügeleisen, Handbohrmaschinen, Schleif- und Schneidgeräte werden durch den Anschluss langer 2- oder 3-adriger Kabel an den Netzstecker mit Strom versorgt.Durch den längeren Gebrauch sind die Drähte des Netzkabels mechanischen Belastungen und Spannungen ausgesetzt, die an jeder Stelle zum Abbrechen der Drähte im Inneren führen können.  In einem solchen Fall entscheiden sich die meisten Menschen für den Austausch des Kerns/Kabels, da es schwierig ist, die genaue Position eines gebrochenen Drahtes zu finden. Die hier vorgestellte Schaltung kann einfach und schnell einen gebrochenen/fehlerhaften Draht und dessen Bruchstelle in 1-adrigen, 2-adrigen und 3-adrigen Kabeln erkennen, ohne die Drähte physisch zu stören. Diese Schaltung ist mit dem CD4069 Hex-Wechselrichter aufgebaut.
