# Projektblog-Catch-the-bone

[Idee](#eins)

[Script Erklärung](#zwei)

[Definition Broadcast Blöcke](#zwei.eins)

[2. Laser](#zwei.zwei)

[3. Winner](#zwei.drei)

[4. Game over](#zwei.vier)

[5. Aliens](#zwei.fünf)

[6. Explosion](#zwei.sechs)

[Spielanleitung](#drei)

[Unsere noch nicht umgesetzten Ziele](#vier)

[Fazit](#fünf)

Catch the bone: https://snap.berkeley.edu/snapsource/snap.html#present:Username=elisavictoria&ProjectName=Catch%20the%20bone

[Idee](#eins)

Auf der Suche nach einem neuen Projekt, wollten wir als "Experten" ;) ein anspruchsvolleres Spiel programmieren. Im Internet sind wir auf verschiedene Spielbeispiele gestoßen und da uns keines dieser angesprochen hat, haben wir uns ein eigenes Spiel überlegt. Inspiriert von unserer Liebe zu Hunden kamen wir auf "Catch the Bone". In dem Spiel soll ein Hund, der von dem Spieler mit den Pfeiltasten gesteuert wird, verschiedene Leckerlies essen. Er hinterlässt auf allen Wegen, die er zurückgelegt hat eine grüne Spur, sodass sich nach und nach ein Netz auf dem Spielfeld spinnt. Die eingesammelten Leckerlies sind gesammelte Punkte vom Spieler, die oben links in der von uns erstellten globalen Variable angezeigt werden. 
Insgesamt wollten wir unser nächstes Spiel auf ein höheres Programmierniveau bringen, indem wir Broadcast Blöcke einsetzten.

[Script Erklärung](#zwei)

[Definition Broadcast Blöcke]<a name="zwei.eins"></a>

Da unser neues Spiel auf der Kommunikation der Items untereinander auf Broadcast Blöcken basiert, ist es zunächst wichtig unser Verständins aufzuzeigen und die Aufgabe dieser speziellen Blöcke zu definieren.

Zu einem Broadcast Block gehört auch immer ein Respond Block. Der Broadcast Block sendet Informationen über das abegspielte Script an den Respond Block, sodass dieser unmittelbar erfährt, wenn ein Ereignis eingetreten ist. Ein Respond Block, der am Anfang eines neuen Scriptes steht, kann nach Nachricht des Broadcast Blockes, eine neue Aktion aktivieren.
Insgesamt ermöglichen die Broadcast und Respond Blöcke eine ganz neue Ebene des Programmierens, indem sie Aktionen und Informationen synchronisieren.



[Spielanleitung](#drei)

Das von uns gewollte, aber noch nicht vollständig programmierte Ziel des Spiels ist, einen bestimmte Anzahl von Leckerlies einzusammeln, also einen festgelegten Score zu erreichen. Das Spiel soll als Verloren gelten, wenn der Hund die von sich slebst gezogene grüne Linie berührt bzw. überschreitet. Der Hund wird von Pfeiltasten gesteuert und geht beim Drücken dieser einen Schritt in die befohlenen Richtung.

[Unsere noch nicht umgesetzten Ziele](#vier)

Man könnte optional noch eine Spielerliste mit Variablen einfügen, was wir auch im Onlinekurs BJC gelernt haben.



[Fazit](#fünf)
