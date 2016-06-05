TeamSpeak 3 Ranking Bot 2.0.6
---------------------------------------------

Inhalte:
	1. Infoblatt
	2. Voraussetzungen
	3. Starten unter Windows
	4. Starten unter Linux
	5. Fehler aufgetreten?
	6. Hilfe zur Findung von Channel IDs?
	7. Feedback 

---------------------

1. Infoblatt:

TeamSpeak 3 Ranking Bot erstellt ein Ranking von aktiven Clients auf dem TeamSpeak 3 Server.

TeamSpeak 3 Ranking Bot Copyright (C) Juni 2016 by xCaptain (elitePvPers).


Die Hauptfunktionen des TeamSpeak 3 Ranking Bot: 

  - Ranking der aktiven Clients erstellen und diese als Textnachricht und in der Beschreibung eines Channels anzeigen
  - Lässt den Client eine Freundesliste erstellen von Clients auf dem TS.
      	- Dadurch kann man schnell sehen ob sein Freund online oder offline ist.
	- Zusätzlich kann man sich zu diesem Freund moven lassen. Sollte man Rechte zu dem Channel haben.
  - Kann von ausgewählten Clients eine Broadcastnachricht verschicken an alle oder bestimmte Gruppen.
  - Kann ein Client nach einer bestimmten Zeit, wenn sein Sound gemutet ist, ihn in einen angegebenen Channel moven.
  - Kann bestimmte Clients eine Poke Nachricht schreiben, wenn ein Client einen bestimmten Channel joint.
  - Verschickt eine Willkommensnachricht an neu gejoint Clients.


TeamSpeak 3 Ranking Bot ist momentan eine freie Software die auf Java basiert. Er funktioniert mit Linux sowie mit Windows.

---------------------

2. Voraussetzungen:

  - einen MySQL Server
  - eine MySQL Datenbank für den Bot
  - Zeiten für die einzelnen Ränge oder die voreingestellten vom Bot
	- zusätzlich die benötigten Gruppen für die Clients im TS -> diese müssen dann in der MySQL Datenbank eingepflegt werden
  - einen Server der rund um die Uhr online ist
  - eingetragene IP vom Bot (IP vom Server auf dem er gestartet ist) beim TeamSpeak 3 Server in die whitelist.txt
  - nicht benutze Befehle in den Configs stehen lassen
	- sollte ein Befehl fehlen startet der Bot nicht

---------------------

3. Starten unter Windows:
  - erstellen einer batch Datei
  - Inhalt: 
	"C:\Pfad\zur\Java\Exe\java.exe" -jar [NAME DER DATEI].jar
  - starten der Batch Datei

---------------------
	
4. Starten unter Linux
  - empfehlenswert Putty zu verwenden
  - Installation von screen um den Bot auch im Hintergrund zu starten
  - Befehl zum starten:
	screen -java -jar [NAME DER DATEI].jar

---------------------

5. Fehler aufgetreten?

  - Schicken Sie mir beide log Dateien
	- per E-Mail an: captainbozz95@gmail.com
	    - WICHTIG mit dem Betreff: TeamSpeak 3 Bot
	      sonst kann es dauern bis auf die Nachricht geantwortet wird
	- PN in elitePvPers : xCaptain

6. Hilfe zur Findung von Channel IDs?

  - Dieses Addon gibt hinter dem Channelnamen die Channel ID an
	http://addons.teamspeak.com/directory/addon/result/Extended-Client-Info.html

---------------------

7. Feedback gerne in diesem Thread: 

http://www.elitepvpers.com/forum/freebies/4064915-teamspeak-3-ranking-bot.html#post34504198
