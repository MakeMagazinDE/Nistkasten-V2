Sollte der Raspberry Zero nach kurzer Zeit kein Kamerabild mehr liefern oder ständig neu booten oder ist das gezeigte Bild überbelichtet,
dann leuchten die IR-LEDs zu stark und nehmen zuviel Strom auf. Wird hingegen bei Tageslicht das Bild des Nestkasten-Inneren plötzlich schwarz, schalten die LEDs zu früh ab.
In beiden Fällen müssen Sie die LEDs mit den Trimmer auf ihren Platinen eingestellen.

Stellen Sie den Trimmer einer der beiden LED so ein, dass sie auch bei zugehaltenem Lichtsensor nicht einschaltet. 
Das Einschalten kann man an einem schwachen roten Glimmen erkennen. 
Den Trimmer der anderen LED stellen Sie so ein, dass die LED bei normaler Tageslicht-Zimmerbeleuchtung eingeschaltet ist und daher schwach rot glimmt.

![Picture](https://github.com/MakeMagazinDE/Nistkasten-V2/blob/main/Hinweise/IRLED.jpg) 


Booten Sie danach den Raspberry erneut, da sich beim Bootvorgang die Kamera auf die Lichtverhaltnisse einstellt.


