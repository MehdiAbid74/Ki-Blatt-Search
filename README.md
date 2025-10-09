# Ki-Blatt-Search
Bonus:
-was Heute gut funktioniert ist : KI-Assistenz+Medezin / Mobile Plattformen und Greifarme sortieren, transportieren und verpacken Waren im 24/7-Betrieb/ routine in Arbeit
-ungelöst:Roboter leisten Logistik, aber echte Beziehungspflege komplexe Entscheidungen und Haftungsfragen bleiben offen/Umwelt Problemen/
------------------------------------------------------
Search.01: 
1)
wir haben (ElbenLinkeSeite,OrkenLinkeSeite,PositionDesPferds)
Startzustand:(3,3,L)=elben und orken sind links und Pferd ist auch links 
Endzustand:(0,0,R)=unserer ziele ist wenn die elben und Orken und pferd sind alle in rechte zeite

2)
Schritte:
<img width="1173" height="709" alt="1,2" src="https://github.com/user-attachments/assets/118e4437-a92e-4c9e-8f8a-996a441d1b90" />

 Sehen 1,2.png
------------------------------------------------------
Search.02:
1)
sehen 2,1-1.png + 2,1-2.png
2)
Nein, die Restkostenabschätzungen dürfen nicht in A* verwendet werden,
weil sie nicht zulässig sind (sie überschätzen die tatsächlichen Restkosten).
um zu  korrigieren
Die Heuristik muss korrigiert werden,
sodass für alle Knoten ℎ(𝑛)≤𝑐(𝑛,𝑛′)+ℎ(𝑛′)h(n)≤c(n,n′)+h(n′)gilt.
Danach kann man A* erneut ausführen mit den korrigierten Werten
------------------------------------------------------
Search.03:
wenn wir sagen h1 dominiert das bedeutet das in alle knoten h₁(n) ≥ h₂(n) -> also die nutzung von h1 fuhrt an einem schnellste und bessere suche 
------------------------------------------------------
Search.04:
A* ist optimal, weil es immer den Knoten mit den kleinsten geschätzten Gesamtkosten 𝑓 ( 𝑛 ) = 𝑔 ( 𝑛 ) + ℎ ( 𝑛 ) f(n)=g(n)+h(n) auswählt. Wenn die Heuristik zulässig ist (also nie zu groß schätzt), dann wird das erste gefundene Ziel immer das mit den minimalen Kosten sein.
