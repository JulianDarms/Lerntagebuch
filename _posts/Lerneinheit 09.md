---
title: "Lerneinheit 12: Suchmaschinen und Discovery-Systeme (Teil 2/2) "
date: 2024-06-03
---

Lerntagebücher
Zu Beginn der Sitzung haben wir uns mit den Anforderungen und Fragen zu den Lerntagebüchern beschäftigt. Die Vorgaben dazu sind in der Semesterinformation in Moodle zu finden. Es war hilfreich, dass uns der Dozent die Möglichkeit gab, Fragen zu Form und Bewertungskriterien auch nach der Sitzung per E-Mail zu stellen. Die Abgabe der Lerntagebücher erfolgt am 30. Juni per E-Mail, entweder als Link zur Webseite oder als Dateianhang in einem beliebigen Format.
Datenintegration in VuFind
Ein wesentlicher Teil der heutigen Diskussion drehte sich um die Integration von konvertierten Daten aus verschiedenen Quellen in VuFind. Diese Daten stammen aus unterschiedlichen Systemen wie Koha, ArchivesSpace, DSpace und DOAJ. Wir haben dabei über die Herausforderungen und die Prozesse gesprochen, die notwendig sind, um diese Daten erfolgreich in VuFind zu importieren. Ein zentraler Punkt war die Notwendigkeit, zuvor importierte Testdaten zu löschen und sicherzustellen, dass alle neuen Daten korrekt zugewiesen und importiert werden.
Ein spezifisches Problem trat beim Import der Daten aus DSpace und ArchivesSpace auf, wo die fehlenden "ID"-Felder zu Fehlern führten. Die Lösung bestand darin, die fehlenden Felder manuell zu ergänzen, um den Import erfolgreich abzuschliessen.
Konfiguration von VuFind
Ein weiterer Schwerpunkt war die Konfiguration von VuFind, die sowohl auf globaler als auch auf lokaler Ebene erfolgen kann. Diese Konfigurationen sind notwendig, um VuFind an die spezifischen Bedürfnisse und Anforderungen einer Bibliothek anzupassen.
•	Globale Konfiguration: Diese befindet sich im Verzeichnis /usr/local/vufind/config/vufind und enthält alle allgemeinen Einstellungen.
•	Lokale Konfiguration: Diese befindet sich im Verzeichnis /usr/local/vufind/local/config/vufind und überschreibt die globalen Einstellungen, wenn vorhanden. Dies stellt sicher, dass benutzerdefinierte Einstellungen bei einem Update nicht verloren gehen.
Wir haben besprochen, wie man die config.ini anpasst, um allgemeine Einstellungen wie das Design oder die Sprache zu ändern. Ebenso wichtig ist die facets.ini, die die Anzeige und das Verhalten der Facetten steuert, welche für die Navigation und Filterung der Suchergebnisse verwendet werden.
Ein konkretes Beispiel für eine Anpassung war die Verschiebung der Facetten von der rechten auf die linke Seite des Bildschirms, was die Benutzerfreundlichkeit verbessern kann. Ebenso haben wir das Design geändert und Funktionen wie die Merkliste aktiviert.
Beispiel Suchportal der HAAB
Wir haben uns das Suchportal der Herzogin Anna Amalia Bibliothek (HAAB) angesehen, das den Suchindex von K10plus-Zentral nutzt. Dieses Portal integriert verschiedene Datenquellen und bietet umfassende Verfügbarkeitsinformationen über Schnittstellen wie PAIA und DAIA. Es zeigt, wie moderne Discovery-Systeme verschiedene Dienste und Datenquellen integrieren können, um den Nutzern eine optimierte Sucherfahrung zu bieten.
Marktüberblick Discovery-Systeme
Abschliessend haben wir einen Marktüberblick über verschiedene Discovery-Systeme erhalten. Hierbei haben wir zwischen kommerziellen und Open-Source-Lösungen unterschieden:
•	Kommerzielle Systeme: Zu den Marktführern gehören Ex Libris mit Primo, OCLC mit WorldCat Discovery und EBSCO mit EDS. Diese Systeme bieten umfassenden Support und regelmässige Updates, sind jedoch auch kostenintensiv.
•	Open-Source-Systeme: VuFind ist eine der bekanntesten Open-Source-Alternativen. Es bietet eine hohe Flexibilität und Anpassungsmöglichkeiten, erfordert jedoch technisches Know-how und Community-Support.
Reflexion
Der heutige Tag hat mir erneut gezeigt, wie vielfältig und komplex das Thema Metadatenmanagement und Discovery-Systeme ist. Besonders die Konfiguration und Anpassung von VuFind war eine wertvolle Erfahrung, die mein Verständnis für die technische Umsetzung solcher Systeme erheblich erweitert hat.
Ein weiterer wichtiger Punkt war der Marktüberblick, der mir einen guten Einblick in die verschiedenen verfügbaren Systeme und ihre Vor- und Nachteile gegeben hat. Es wird klar, dass die Wahl des richtigen Systems stark von den spezifischen Anforderungen und Ressourcen einer Bibliothek abhängt.
