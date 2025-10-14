1)

lässt sich definieren als:

Zustände:	[33100];[32221];[22211]...

Aktionen: 	Pferd geht von ufer a mit b, c nach d
		pferd läd b und/oder c ab


Start zustand: 	3  3  1  0  0
		o1 e1 p o2 e2
		wobei o1 und e1 die anzahl Elben/Orks an Ufer 1 darstellen
		o2, e2, das gleiche nur für Ufer 2,
		und P stellt dar wo sich das Pferd befindet (1 = Ufer 1...)
		
End zustand:	0  3  2  3  3

		
        graph viz skript:
        oder Graphik_01

        https://graph.flyte.org/#digraph%20G%20%7B%0D%0A%20node%20%5Bshape%3Dcircle%5D%3B%0D%0A%20%2223110%22%3B%0D%0A%20%2213220%22%3B%0D%0A%20%2211222%22%3B%0D%0A%20%2203230%22%3B%0D%0A%20%2220113%22%3B%0D%0A%20%2222211%22%3B%0D%0A%20%2210123%22%3B%0D%0A%20%2230103%22%3B%0D%0A%20%2200233%22%20%5Bcolor%3Dgold%2C%20style%3Dfilled%5D%3B%0D%0A%20%2223210%22%3B%0D%0A%20%2213120%22%3B%0D%0A%20%2222111%22%3B%0D%0A%20%2211122%22%3B%0D%0A%20%2233100%22%20%5Bcolor%3Dgreen%2C%20style%3Dfilled%5D%3B%0D%0A%20%2220213%22%3B%0D%0A%0D%0A%20%2233100%22%20-%3E%20%2213220%22%20%5Blabel%3D%222O%2B0E%22%5D%3B%0D%0A%20%2233100%22%20-%3E%20%2223110%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%20%2233100%22%20-%3E%20%2230103%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%20%2233100%22%20-%3E%20%2223210%22%20%5Blabel%3D%220O%2B1E%22%5D%3B%0D%0A%20%2233100%22%20-%3E%20%2222211%22%20%5Blabel%3D%221O%2B1E%22%5D%3B%0D%0A%0D%0A%20%2213220%22%20-%3E%20%2223110%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%20%2213220%22%20-%3E%20%2233100%22%20%5Blabel%3D%222O%2B0E%22%5D%3B%0D%0A%0D%0A%20%2223110%22%20-%3E%20%2203230%22%20%5Blabel%3D%222O%2B0E%22%5D%3B%0D%0A%20%2223110%22%20-%3E%20%2213120%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%20%2223110%22%20-%3E%20%2233100%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%0D%0A%20%22032030%22%20%2F*%20(nicht%20existent)%20*%2F%20%3B%0D%0A%0D%0A%20%2213120%22%20-%3E%20%2211122%22%20%5Blabel%3D%220O%2B2E%22%5D%3B%0D%0A%20%2213120%22%20-%3E%20%2223110%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%0D%0A%20%2211122%22%20-%3E%20%2200233%22%20%5Blabel%3D%221O%2B1E%22%5D%3B%0D%0A%20%2211122%22%20-%3E%20%2210223%22%20%5Blabel%3D%220O%2B1E%22%5D%3B%0D%0A%0D%0A%20%2200233%22%20-%3E%20%2210123%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%20%2200233%22%20-%3E%20%2220113%22%20%5Blabel%3D%222O%2B0E%22%5D%3B%0D%0A%20%2200233%22%20-%3E%20%2211122%22%20%5Blabel%3D%221O%2B1E%22%5D%3B%0D%0A%0D%0A%20%2210123%22%20-%3E%20%2200233%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%0D%0A%20%2220113%22%20-%3E%20%2210223%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%20%2220113%22%20-%3E%20%2200233%22%20%5Blabel%3D%222O%2B0E%22%5D%3B%0D%0A%0D%0A%20%2210223%22%20-%3E%20%2220113%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%20%2210223%22%20-%3E%20%2230103%22%20%5Blabel%3D%222O%2B0E%22%5D%3B%0D%0A%20%2210223%22%20-%3E%20%2211122%22%20%5Blabel%3D%220O%2B1E%22%5D%3B%0D%0A%0D%0A%20%2230103%22%20-%3E%20%2220213%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%20%2230103%22%20-%3E%20%2210223%22%20%5Blabel%3D%222O%2B0E%22%5D%3B%0D%0A%0D%0A%20%2220213%22%20-%3E%20%2230103%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%20%2220213%22%20-%3E%20%2222111%22%20%5Blabel%3D%220O%2B2E%22%5D%3B%0D%0A%0D%0A%20%2222111%22%20-%3E%20%2220213%22%20%5Blabel%3D%220O%2B2E%22%5D%3B%0D%0A%20%2222111%22%20-%3E%20%2220113%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%0D%0A%20%2222211%22%20-%3E%20%2233100%22%20%5Blabel%3D%221O%2B1E%22%5D%3B%0D%0A%0D%0A%20%2223210%22%20-%3E%20%2233100%22%20%5Blabel%3D%220O%2B1E%22%5D%3B%0D%0A%20%222310%22%20-%3E%20%2223110%22%20%5Blabel%3D%221O%2B0E%22%5D%3B%0D%0A%0D%0A%20%2223110%22%20-%3E%20%2213220%22%20%5Blabel%3D%222O%2B0E%22%5D%3B%0D%0A%20%2213120%22%20-%3E%20%2213120%22%20%5Blabel%3D%220O%2B0E%22%5D%3B%20%2F*%20Platzhalter%2C%20kein%20g%C3%BCltiger%20Move%20*%2F%0D%0A%7D%0D%0A
        
```bash
digraph G {
 node [shape=circle];
 "23110";
 "13220";
 "11222";
 "03230";
 "20113";
 "22211";
 "10123";
 "30103";
 "00233" [color=gold, style=filled];
 "23210";
 "13120";
 "22111";
 "11122";
 "33100" [color=green, style=filled];
 "20213";

 "33100" -> "13220" [label="2O+0E"];
 "33100" -> "23110" [label="1O+0E"];
 "33100" -> "30103" [label="1O+0E"];
 "33100" -> "23210" [label="0O+1E"];
 "33100" -> "22211" [label="1O+1E"];

 "13220" -> "23110" [label="1O+0E"];
 "13220" -> "33100" [label="2O+0E"];

 "23110" -> "03230" [label="2O+0E"];
 "23110" -> "13120" [label="1O+0E"];
 "23110" -> "33100" [label="1O+0E"];

 "032030" /* (nicht existent) */ ;

 "13120" -> "11122" [label="0O+2E"];
 "13120" -> "23110" [label="1O+0E"];

 "11122" -> "00233" [label="1O+1E"];
 "11122" -> "10223" [label="0O+1E"];

 "00233" -> "10123" [label="1O+0E"];
 "00233" -> "20113" [label="2O+0E"];
 "00233" -> "11122" [label="1O+1E"];

 "10123" -> "00233" [label="1O+0E"];

 "20113" -> "10223" [label="1O+0E"];
 "20113" -> "00233" [label="2O+0E"];

 "10223" -> "20113" [label="1O+0E"];
 "10223" -> "30103" [label="2O+0E"];
 "10223" -> "11122" [label="0O+1E"];

 "30103" -> "20213" [label="1O+0E"];
 "30103" -> "10223" [label="2O+0E"];

 "20213" -> "30103" [label="1O+0E"];
 "20213" -> "22111" [label="0O+2E"];

 "22111" -> "20213" [label="0O+2E"];
 "22111" -> "20113" [label="1O+0E"];

 "22211" -> "33100" [label="1O+1E"];

 "23210" -> "33100" [label="0O+1E"];
 "2310" -> "23110" [label="1O+0E"];

 "23110" -> "13220" [label="2O+0E"];
 "13120" -> "13120" [label="0O+0E"]; /* Platzhalter, kein gültiger Move */
}

```
**2**

Frankfurt -> Mannheim 85
Frankfurt -> Würzburg 217
Frankfurt -> Kassel 173

Mannheim -> Frankfurt 85
Mannheim -> Karlsruhe 80

Karlsruhe -> Mannheim 80
Karlsruhe -> Ausburg 250

Würzburg -> Erfurt 186
Würzburg -> Nürnbern 103

Nürnbern -> Stuttgart 183
Nürnbern -> Würzburg 103
Nürnbern -> München 167

Kassel -> München 502

Breitensuche:

Frankfurt = F
Mannheim = M
Würzburg = W
Kassel = K
Karlsruhe = Kr
Nürnberg = N
Stuttgart = S
München = Mü
Augsburg = A



