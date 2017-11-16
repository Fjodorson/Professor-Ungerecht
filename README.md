# Professor-Ungerecht
Hausaufgabe-EPR

Aufgabe 2.2: Professor Ungerecht Punkte: / 5
Professor Ungerecht hat eine sehr eigene Bewertungsmethode.
Zun¨achst ermittelt er die Vornoten der Pr¨ufungsleistungen f¨ur Module nach den Vorgaben
des § 26 Absatz 2 bis 4 der Bachelorordnung Informatik, siehe http://www.cs.
uni-frankfurt.de/images/pdf/informatik/bachelor2/bachelorordnung_neu.pdf.
Dann ”korrigiert“ er die Note:
1Es d¨urfen keine L¨osungen aus dem Skript, dem Internet oder anderen Quellen abgeschrieben werden. Diese Quellen
d¨urfen nur mit Quellenangaben verwendet werden und es muss ein hinreichend großer Eigenanteil in den L¨osungen deutlich
zu erkennen sein.
Kontrollstrukturen ¨ Ubungsblatt Nr. 2
• Ist die Person weiblich, verbessert er die Note um 0.4 Notenwerte.
• Ist die Person gr¨oßer als 180 cm (der K¨orpergr¨oße von Professor Ungerecht), so
addiert er f¨ur jeden weiteren cm 0,05 Notenpunkte auf den bereits ermittelten
Notenwert.
• Abschließend rundet er die Note gem¨aß der Vorgaben der Pr¨ufungsordnung.
Als Hardcore-Informatiker hat sich Professor Ungerecht zur Berechnung ein Assembler-
Programm geschrieben, das als Eingabe einen String der Form
Vornote Geschlecht K¨orpergr¨oße (alles in einer Zeile, getrennt jeweils
durch ein Leerzeichen, ohne prompt).
von der Konsole erwartet, mit folgenden Einschr¨ankungen:
• Die Vornote wird als Float-Literal notiert, immer mit genau drei Zeichen, z.B.
2.3 oder 3.0 Geschlecht wird mit einem Zeichen kodiert: w steht f¨ur weiblich,
jedes andere Zeichen steht f¨ur nicht weiblich.
• Die K¨orpergr¨oße wird als Integer in cm angegeben, immer dreistellig im Intervall
[100,300], z.B. 185 f¨ur 0,25 Zuschlag zum Notenwert.
• Als Ergebnis gibt das Programm dann die gerundete ”korrigierte“ Note aus.
Tun Sie es Professor Ungerecht nach. Schreiben Sie auch ein solches Programm in Python
3.6. Sie d¨urfen davon ausgehen, dass die Syntax der Eingabe pr¨azis eingehalten
wird, m¨oglicherweise aber nicht die Wertebereiche.
¨Uberlegen Sie genau, was der Nutzer Ihres Programms alles falsch machen k¨onnte und
fangen Sie diese Fehler ab. ¨Uberpr¨ufen Sie dies durch geeignete Testf¨alle (entsprechend
des ¨Uberblicks zum Testen, welcher in der Vorlesung gegeben wird). Falls unzul¨assige
Werte eingegeben werden, geben Sie ERROR aus.
