# LDAP

Gruppe Adler/Karic/Kopec

Realisierung einer zentralen Benutzerverwaltung für ein Unternehmen
Ausgangssituation
Sie sind als Netzwerk- und Systemadministrator für bei einem Startup-Unternehmen angestellt worden. Dieses benötigt eine Vielzahl von Netzwerk-Services (Mail, Web, Filesharing, Drucken, Login am Desktop, ...) für die eine zentrale Benutzerverwaltung eingeführt werden soll.

Die Mitarbeiter des Unternehmens arbeiten mit heterogenen Systemen - manche unter Linux, machen unter Windows, manche unter Mac OS und einige mit FreeBSD. Die zentrale Authentifizierung soll bei all diesen Systemen funktionieren. Als nice-to-have Feature wünscht sich das Unternehmen eine Single-Sing-On-Lösung.

Aufgabenstellung
Installieren und Konfigurieren Sie für dieses Unternehmen eine zentrale Benutzerverwaltung auf Basis von OpenLDAP. Stellen Sie einfache Mittel zur Verwaltung von Benutzeraccounts und -gruppen zur Verfügung, mit denen Sie Benutzer und Gruppen anlegen, bearbeiten und verwalten können. Ebenso sollen die Berechtigungen der Benutzer modifizierbar sein. Um die Verfügbarkeit des Systems zu garantieren soll der Verzeichnisdienst automatisch replizieren (Master-Slave oder Master-Master).

Richten Sie weiters einen zentralen Webserver mit sicherem FTP-Zugang ein; nur Benutzer aus der Gruppe "Web-Administratoren" sollen diesen FTP-Zugang verwenden können.

Richten Sie einen Fileserver für das Unternehmen ein, in dem jeder Benutzer ein eigenes Heimatverzeichnis besitzt sowie für verschiedene Gruppen (Entwicklung, Marketing, ...) gemeinsame Ordner.

Richten Sie weiteres einen Mailserver (SMTP, IMAP, Webmail) ein, mit dem alle Benutzer Mails senden und empfangen können. Für alle Gruppen soll automatisch ein Mail-Verteiler erstellt werden. Der Mailserver soll weiters einen integrierten Spam- und Virenfilter beinhalten.

Konfigurieren Sie mindestens einen Windows-Client und einen Linux-Client so, dass diese zusätzlich zur Anmeldung mit lokalen Benutzern die Anmeldung mit Benutzern aus dem Verzeichnisdienst zulassen.

Abgabe
Planen Sie die gesamte Netzwerkinfrastruktur sowie eine vernünftige Aufgabenaufteilung auf die verschiedenen Teammitglieder.

Demonstrieren Sie am Ende jeder Stunde den aktuellen Fortschritt.

Dokumentieren Sie sämtliche durchgeführten Konfigurationsschritte, Problemstellungen und Tests.

Die Arbeit in Gruppen (maximal 3 Personen, andere Gruppenzusammenstellung als bei der letzten Übung!) ist erlaubt.
