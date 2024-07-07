---
title: "Lerneinheit 11: Suchmaschinen und Discovery-Systeme (Teil 1/2) "
date: 2024-02-14
---

In der heutigen Sitzung haben wir uns zunächst mit einem Nachtrag zum Thema Metadatenmodellierung und Schnittstellennutzung beschäftigt. Hierbei standen die ETL-Prozesse (Extract, Transform, Load) im Fokus, die für die Verarbeitung und Integration von Daten entscheidend sind.
ETL-Prozesse: Diese Prozesse sind essenziell für die Datenverarbeitung in Bibliotheken und Archiven. Sie ermöglichen das Extrahieren von Daten aus verschiedenen Quellen, deren Transformation in ein einheitliches Format und schliesslich das Laden in Zielsysteme. Ein Beispiel hierfür ist das OPAC-NG-Projekt des Deutschen Literaturarchivs Marbach, das einen modernen Online-Katalog bereitstellt und eine umfassende Systemarchitektur aufweist.
Weitere Tools zur Metadatentransformation
Wir haben uns verschiedene Tools zur Metadatentransformation angeschaut, darunter:
•	Catmandu: Ein in Perl geschriebenes Tool, das für die Verarbeitung von Metadaten nützlich ist.
•	Metafacture: Eine Java-basierte Software, die für die flexible Verarbeitung und Transformation von Metadaten eingesetzt wird.
•	MarcEdit: Ein Tool speziell für MARC21-Daten, das weit verbreitet ist und eine Vielzahl von Funktionen bietet.
Ein wichtiges Kriterium bei der Wahl der richtigen Software ist der spezifische Anwendungsfall. Oft wird die Software verwendet, die den Anwendern bereits vertraut ist. Für diejenigen, die Python beherrschen, gibt es beispielsweise die Library PyMARC zur Verarbeitung von MARC21-Daten.
Einführung in VuFind und Solr
Nachdem wir in den letzten Veranstaltungen Daten produziert haben, ging es heute darum, diese in ein Discovery-System zu integrieren. Hierbei haben wir VuFind verwendet, eine Open-Source-Software, die auf Apache Solr basiert.
VuFind: VuFind ist ein Discovery-System, das speziell für Bibliotheken entwickelt wurde. Es ermöglicht die Suche nach bibliografischen Daten, Open-Access-Artikeln und anderen Ressourcen. Die Software bietet eine benutzerfreundliche Oberfläche und unterstützt verschiedene Metadatenformate wie MARC21.
Solr: Apache Solr ist eine leistungsstarke Suchplattform, die für Volltextsuche und Indexierung genutzt wird. Sie ist nicht nur im Bibliotheksbereich, sondern auch in vielen kommerziellen Anwendungen weit verbreitet. Solr bietet eine flexible und effiziente Möglichkeit, grosse Datenmengen zu durchsuchen und relevante Ergebnisse zu liefern.
Installation und Konfiguration von VuFind
Die Installation von VuFind erfolgte nach der offiziellen Anleitung für Ubuntu. 
Nach der Installation haben wir Testdaten im MARC21-Format in VuFind importiert, um die Funktionalität der Software zu prüfen.
Suchmaschinen und Discovery-Systeme
In einem zweiten Teil der Sitzung haben wir die Funktionsweise von Suchmaschinen und Discovery-Systemen untersucht. Dabei lag der Fokus auf der Gegenüberstellung von VuFind und Solr.
Unterschiede zwischen VuFind und Solr:
•	VuFind bietet eine benutzerfreundliche Oberfläche für Endnutzer, während Solr eine technische Suchoberfläche für Administratoren bereitstellt.
•	VuFind ermöglicht eine umfassende Suche mit Facetten und relevanzbasierten Ergebnissen, die für eine einfache und intuitive Nutzung optimiert sind.
•	Solr hingegen ist stärker auf die lexikalische Suche und die Verarbeitung von grossen Datenmengen ausgelegt.
Vergleich der Suchfunktionen:
•	In VuFind konnten wir durch die Eingabe von Suchbegriffen wie "psychology" schnell relevante Ergebnisse finden und diese weiter verfeinern.
•	In der Solr-Administrationsoberfläche haben wir ähnliche Suchanfragen durchgeführt, wobei die Ergebnisse in einer technischeren Form präsentiert wurden.
Reflexion
Der heutige Tag hat gezeigt, wie wichtig es ist, geeignete Werkzeuge für die Metadatenverarbeitung und die Suche in Bibliothekskatalogen zu wählen. VuFind und Solr bieten beide leistungsstarke Funktionen, die je nach Anwendungsfall unterschiedliche Vorteile bieten. Während VuFind eine benutzerfreundliche Lösung für Endnutzer darstellt, bietet Solr eine robuste Plattform für die Verwaltung und Verarbeitung grosser Datenmengen.

