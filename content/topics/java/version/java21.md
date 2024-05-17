# Java 21

https://www.youtube.com/watch?v=88pD1JFP0iU&t=122s -> minute 29

2x 1h

## Erster Workshop
- Einführung, warum dieser Kurs?
	- Ziele
		- Java 21 Features anwenden können
			- aber nicht müssen
	- Was lernen wir? 
		- Records
		- Sealed classes (in Java17)
			- sealed interface Shape permits Circle, Rect {...}
		- Algebraic data types = Records + sealed classes
			- sealed interface Expr { record SumExpr(Expr left, Expr right) implements Expr{} ...}
		- Pattern matching
			- if (x instanceof String s) 
				- directly define s
			- Composing patterns
				- if (shape instanceof Circle(Point(var cx, var cy), int r))) { // use cx, cy, r}
				- unused components "_"
					- if (shape instanceof Circle(Point(var cx, var cy), int r))) { // use cx, cy, _}
		- Revamp of switch
		- Text blocks
- Warmup Übung
	- Codebeispiel in Java8 geschrieben
		- Public Projekt in Github.com
	- Lösungsfindung in Pairs
		- Internetrecherchen
	- Gemeinsame Diskussion, ob Lösung in Java21 nun besser sein sollte
		- In selbem Projekt auf Lösungsbranch
- Weitere Neuerungen, ca 10min
	- Nur Folien
		- Tonspur, aber unterhaltsam
- Abschlussübung im Mob
	- Codebeispiel in Java8 geschrieben
		- Public Projekt in Github.com
	- Lösungsfindung im Mob
		- Internetrecherchen
	- Kurze gemeinsame Diskussion, ob Lösung in Java21 nun besser sein sollte
		- In selbem Projekt auf Lösungsbranch
- Abschluss
	- Kurzer Rückblick mit Lerninhalten
	- Rückmeldungen zum Kurs
		- Was wollen sie mitnehmen in die Praxis?
	- Ausblick Themen nächster Kurs
	- Fragen zum heutigen Teil im Voraus per Mail melden, damit man sich darauf vorbereiten kann

## Zweiter Workshop
- Rückblick erster Teil
- Sind Fragen aufgetaucht?
	- Diese klären
	- Spontane Fragen auch versuchen zu klären oder auf per Mail vertrösten
- Konnten sie bereits was umsetzen im Code?
- Warmup Übung analog erster Teil
- Weitere Neuerungen analog erster Teil
- Abschlussübung analog erster Teil
- Abschluss
	- Rückblick mit Lerninhalten
	- Rückmeldungen zum ganzen Kurs
	- Ausblick auf weitere Kurse