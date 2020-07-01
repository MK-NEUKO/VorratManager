# VorratManager

Der VorratManager im folgenden VM genannt, besteht im wesentlichen aus drei Teilen. Es ist eine Client Server Anwendung. Der erste Teil ist eine Datenbank. Der zweiter Teil ist eine Desktopanwandungen und der dritte Teil eine Mobile App. Die Desktopanwandungen soll hauptsächlich unter Windows laufen, ich möchte mir aber offen halten, dass das Programm auch auf anderen Systemen laufen könnte. Die mobile Version ist für Android gedacht.

	1. Datenbank
Die Datenbank soll durch eine MySQL-Datenbank realisiert werden. Die Kommunikation ist vorzugsweise über LAN bzw. WLAN gedacht.
Ein Homeserver währe die bevorzugte Umgebung. 
	 
	2. Desktopanwandungen
Die Desktopanwandungen ist das Herzstück und beinhaltet die meiste Funktionalität.
• Eingabe eines Datensatzes, bestehen aus, Artikelbezeichnung, Hersteller, MHD, Inhalt in Volumen, Anzahl pro Volumen, Lagerort Lagerunterort, Kategorie, Barcode
  Es können noch weiterehinzukommen.
• Generieren eines Barcode für jeden Artikel 
• Anzeigen der Artikel, verschieden sortiert
• Anzeigen einer Baumstruktur nach Kategorie
• Anzeigen einer Baumstruktur nach Ort-Unterort 
• Meldung zum MHD, ablaufende Artikel
• Ausdrucken verschieden sortierter Listen in Tabellenform. 
Das sind nur die Grundfunktionen, mehr kann bei der Entwicklung noch einflißen. 

	3. Mobile App 
Die App soll grundsätzlich etwa den gleichen Funktionsumfang aufweisen, wie die Desktopanwandungen.
Die Hauptfunktion der Mobile App ist ein Scanner fur den Barcode. Es soll, zur vereinfachten Entnahm und zum Wiederauffüllen des Lagers nur der Barcode gescannt werden. Dann muss nur Änderungen, wie MHd od. Anzahl aktualisiert werden.
