Herzlich Wilkommen zum Waiter-Kitchen View des Webtech Projektes von Konstantin Benischke und Christof Plieschnegger (Team 3, Gruppe 3) 

Arbeitsaufteilung:
Während der Großteil der Typescript Dateien von Konstantin implementiert wurden, ist der größte Teil der CSS und HTML Dateien von
Christof geschrieben worden. Wir haben uns jedoch nicht auf bestimmte Teile des Projektes festgelegt, sondern
standen beinahe jeden Tag seit Beginn des Projektes mehrere Stunden auf Discord in Kontakt, um über neue Ideen zu diskutieren
und auch Arbeiten des jeweils anderen zu erledigen. Daher spreche ich zwar jeder Person einen Großteil eines Gebietes zu,
aber jeder kam mit dem gesamten Code des Projektes in Berührung.

Mögliche Status einer Order:
	Im Kitchen View:
		Ordered: Diesen Status erhält eine Order direkt nachdem sie aufgegeben wurde und noch nicht in Bearbeitung ist oder die Items 
			als "In-Production" gekennzeichnet sind
		Incomplete: Diesen Status erhält die Order nachdem mindestens ein Item der Order als "Ready-for-pickup" gekennzeichnet wurde
	
	Im Waiter View:
		Incomplete: Sobald der Kitchen View ein Item als "Ready-for-pickup" markiert erhält der Waiter View dieses unter dem Punkt
			"Incomplete Orders", eine Order bleibt hier so lange bis alle Items aus dieser Order als "delivered" gekennzeichnet wurden
		Complete: Diesen Status erhält eine Order nachdem sie komplett abgearbeitet wurde (alle Items delivered), sie ist nun unter dem Punkt
			"Orders" im Waiter View zu finden
		Delivered: Einzelne Items erhalten diesen Status nachdem sie delivered wurden

Sämtliche Status können nicht rückwärts durchlaufen werden, um dies zu erreichen werden nicht mehr erreichbare Buttons disabled.
Beispielsweise kann ein Item nicht von "Ready-for-pickup" auf "In-Production" gesetzt werden.
	

Im Abgabeordner finden Sie neben dieser Datei noch den Source Code des Projektes und ein 8-minütiges Video, welches alle
Funktionalitäten des Waiter-Kitchen Views zeigt.
