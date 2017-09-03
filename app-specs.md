# Spezifikation der App

## Seiten
* Anmelden
* Einloggen
* Frage stellen
* Fragen entdecken
* Offene Fragen
* Beantwortete Fragen
* Top Fragen
* Info

## Anmelden
* Passwort mit mind. 8 Zeichen
* E-Mail und Passwort sind Pflicht, alles andere optional

## Einloggen
TBD

## Frage stellen
Hier kann der User eine neue Frage stellen. Die Frage muss ein bis drei #Tags haben
und aus 10 bis 250 Zeichen bestehen.

Um eine Frage stellen zu können, muss der User mindestens 10 Fragen bewertet haben.

## Fragen entdecken
Hier werden zufällig Fragen angezeigt, die der User noch nicht bewertet hat
und die noch nicht beantwortet sind, bzw. an die Politiker weitergereicht wurden.

Der User kann Fragen mit Tippen oder Wischen als gut oder schlecht bewerten.

## Offene Fragen
Hier werden alle Fragen angezeigt, die der User positiv bewertet hat
und die noch nicht beantwortet sind, bzw. an die Politiker weitergereicht wurden.

## Beantwortete Fragen
Hier wird ganz oben die Frage angezeigt, die aktuell die meisten positiven Bewertungen
hat und daher an die Politiker weitergereicht wurde.

Darunter werden alle Fragen angezeigt, die bereits beantwortet wurden, wobei die Frage
mit den neuesten Antworten oben steht.

Vom Backend muss diese Liste abgefragt werden können, ab besten schon mit der richtigen
Sortierung.

## Top Fragen
Wenn kein #Tag ausgewählt ist, werden alle Fragen unabhängig von ihrer Bewertung durch
den User aufgelistet und nach Beliebtheit sortiert.
Das können sehr viele Fragen sein, daher sollten weitere Fragen erst nachgeladen werden,
wenn der User nach unten scrollt. Das wiederum erfordert, dass die Fragen bereits im
Backend sortiert werden.

Durch auswählen von #Tags kann die Liste der Fragen eingeschränkt werden.

Der User kann Fragen mit Tippen oder Wischen als gut bewerten, auch wenn diese vorher
von ihm als schlecht bewertet wurde.

## Info
Hier wird zuerst die Übereinstimmung der Antwort-Bewertung mit den Parteien angezeigt.

Darunter werden alle Info-Beiträge angezeigt, die neuesten zuerst.
