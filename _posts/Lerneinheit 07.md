---
title: "Lerneinheit 10: Metadaten modellieren und Schnittstellen nutzen B (Schnittstellen) (Teil 3/3) "
date: 2024-02-14
---


Heute haben wir uns intensiv mit dem Thema Metadatenmodellierung und der Nutzung von Schnittstellen beschäftigt. Dabei lag der Schwerpunkt auf der praktischen Anwendung von Austauschprotokollen und der Konvertierung von Metadaten. Hier eine Zusammenfassung der wichtigsten Punkte und Erkenntnisse des Tages:
Ausgangsdaten und ihre Bedeutung
Zum Einstieg haben wir die Ausgangsdaten aus verschiedenen Systemen wie Koha, ArchivesSpace und DSpace untersucht. Diese Systeme bieten Metadaten in verschiedenen Formaten an, darunter MARCXML, EAD und Dublin Core. Unsere Aufgabe bestand darin, diese Datenformate zu sammeln und in einheitliche Formate zu konvertieren, um eine konsistente Datenbasis zu schaffen.
Schnittstellen: Austauschprotokolle für Metadaten
Im nächsten Schritt haben wir uns mit den gängigen Austauschprotokollen für Metadaten befasst. Diese Protokolle sind entscheidend für den Datenaustausch zwischen verschiedenen Systemen und Plattformen.
1.	Z39.50: Ein altes, aber immer noch verwendetes Netzwerkprotokoll, das insbesondere für Live-Abfragen und gezielten Datenabruf genutzt wird. Es ermöglicht den Zugriff auf bibliografische Datenbanken und den Abruf von Metadaten in verschiedenen Formaten wie MARC21 und Dublin Core.
2.	SRU (Search/Retrieve via URL): Ein moderneres Protokoll, das auf XML basiert und Suchanfragen über URLs ermöglicht. Es wird häufig als Ergänzung zu Z39.50 verwendet und ist besonders benutzerfreundlich, da die Anfragen direkt über den Browser gestellt werden können.
3.	OAI-PMH (Open Archives Initiative Protocol for Metadata Harvesting): Dieses Protokoll ist speziell für grössere Datenabzüge und regelmässige Aktualisierungen konzipiert. Es ermöglicht das Harvesten von Metadaten aus verschiedenen Quellen und wird häufig in Bibliotheken und Archiven eingesetzt.
Praktische Anwendung: Metadaten harvesten mit VuFindHarvest
Ein besonderer Fokus lag heute auf der praktischen Anwendung des OAI-PMH-Protokolls mit dem Tool VuFindHarvest. Wir haben uns durch folgende Schritte gearbeitet:
1.	Vorbereitung: Zunächst haben wir den Codespace mit einem vorbereiteten Repository aufgerufen und in das Verzeichnis von VuFindHarvest gewechselt.

2.	Ermittlung des Metadatenformats: Für die jeweiligen Systeme (Koha, ArchivesSpace, DSpace) haben wir die verfügbaren Metadatenformate über deren OAI-PMH-Basisurl ermittelt.

3.	Harvesting: Wir haben die entsprechenden Kommandos ausgeführt, um die Metadaten abzurufen. 
Konvertierung von Metadaten
Nach dem Harvesting der Metadaten haben wir uns mit deren Konvertierung beschäftigt. Diese wird als Crosswalk bezeichnet und beschreibt den Prozess der Umwandlung von einem Metadatenstandard in einen anderen.
1.	XSLT Crosswalks: Hierbei handelt es sich um die Verwendung der Programmiersprache XSLT (Extensible Stylesheet Language Transformations), um XML-Dokumente zu transformieren. Dies ist besonders nützlich, um Metadaten von einem Format wie Dublin Core in ein anderes wie MARC21 zu konvertieren. Die Library of Congress bietet beispielsweise vorgefertigte XSLT-Scripte an, die diese Transformationen unterstützen.
2.	Beispiele und Tools: Wir haben verschiedene Tools wie xsltransform.net und MarcEdit kennengelernt. Während xsltransform.net für einfache Transformationen genutzt werden kann, ist MarcEdit besonders für komplexere Aufgaben geeignet, da es eine Vielzahl von nützlichen XSL-Scripten für den Bibliotheksbereich mitliefert.
Reflexion und Ausblick
Der heutige Tag hat gezeigt, wie wichtig und komplex die Arbeit mit Metadaten sein kann. Die Nutzung von Austauschprotokollen und die Konvertierung von Datenformaten sind entscheidende Schritte, um konsistente und qualitativ hochwertige Metadaten zu gewährleisten. Besonders beeindruckend war die praktische Anwendung der OAI-PMH-Schnittstelle mit VuFindHarvest, die den Prozess des Harvesting und der anschliessenden Konvertierung deutlich vereinfacht.
