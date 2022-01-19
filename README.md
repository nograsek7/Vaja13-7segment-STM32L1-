# Vaja13-7segment-STM32L1-

V Pinout & Configuraton pogledu glede na vašo razvojno ploščico postavite 7 prvih prostih pinov skupine A na GPIO_Output. Pine označite (label) s črkami segmenta: a, b, c, d, e, f in g.  
Zapišite izbrane (konfigurirane) pine:
	Segment a: __PA1___  	 
	Segment b: _PA2___  	Segment e: __PA5___  
	Segment c: __PA3___  	Segment f: ___PA6__  
	Segment d: __PA4___  	Segment g: ____PA7_ 

7-segmentni display je lahko v izvedbi skupne anode ali skupne katode. Vaš prikazovalnik testirate tako, da ga zvežete po spodnji (levi ali desni) shemi in preizkusite, katera polariteta je ustrezna (rdeča 5V, modra GND): 
Vaš prikazovalnik je s skupno __katoda_________. Preverite delovanje še preostalih segmentov! 

Kaj dela ukaz GPIOA -> ODR ?  
__GPIOA nastavi na odrodr je 16 bitni register__

Opazujte delovanje 7-segmentega prikazovalnika. Kaj se zgodi, ko pritisnemo črno tipko na STM32L1? 
____Resetera se oz. začne šteti od začetka____

Komentar:
V PDF dokumetu pri 2. nalogi e primer je 0 - la napačno definirana z ničlami pa enkami.
Ostalih večjih problemov nismo imeli oz. jih nismo zaznali.
7 segmentni displej se je lepo in enakomerno spreminjal. Tudi z črno tipko reset nismo imeli težav, saj se je vsakič ko si jo pritisnil lepo štelo od začetka.


Luka Nograšek, Luka Buzina, Žiga Kuder
