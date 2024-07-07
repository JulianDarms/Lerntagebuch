---
title: "Lerneinheit 13: Linked Data "
date: 2024-06-03
---

Heute haben wir uns intensiv mit verschiedenen aktuellen Themen in der Bibliotheks- und Archivinformatik beschäftigt. Unsere Schwerpunkte lagen auf den aktuellen Datenmodellen für Metadaten, insbesondere BIBFRAME und Records in Context (RiC), sowie dem Konzept Linked Open Usable Data (LOUD).
Aktuelle Datenmodelle für Metadaten
BIBFRAME
BIBFRAME (Bibliographic Framework) wurde als Nachfolger von MARC21 entwickelt und basiert auf den Prinzipien der Functional Requirements for Bibliographic Records (FRBR) sowie den Resource Description and Access (RDA). Seit 2012 wird es von der Library of Congress gefördert, um die Metadatenstandards zu modernisieren und besser in das Umfeld des Semantic Web zu integrieren. BIBFRAME 2.0, die aktuellste Version seit 2016, unterscheidet zwischen den Entitäten Work, Instance und Item und definiert die Beziehungen zwischen diesen Entitäten.
•	Work: Die abstrakte Idee eines Werkes.
•	Instance: Eine konkrete Realisierung des Werkes, z.B. eine spezifische Ausgabe.
•	Item: Ein physisches Exemplar der Instance.
Im Gegensatz zu MARC21, das alle Informationen in einem Datensatz bündelt, trennt BIBFRAME die einzelnen Elemente und verwendet kontrollierte Identifikatoren, um redundante Informationen zu vermeiden. Dadurch können Änderungen zentral an einer Stelle vorgenommen werden, was die Datenpflege erleichtert und die Datenkonsistenz erhöht.
Records in Contexts (RiC)
RiC ist ein datenmodellbasierter Ansatz für die archivische Verzeichnung und basiert auf den Prinzipien von Linked Data. Es verbindet die internationalen Standards ISAD(G), ISAAR(CPF), ISDF und ISDIAH, um ein einheitliches und vernetztes System für die Beschreibung von Archivbeständen zu schaffen. RiC ermöglicht es, komplexe Beziehungen zwischen verschiedenen Entitäten darzustellen und die Daten im Kontext zu verknüpfen.
Ein wichtiger Aspekt von RiC ist die Provenienz, also die Herkunft der Daten, die in Archiven eine zentrale Rolle spielt. Durch die Nutzung von Linked Data-Prinzipien können Archivdaten besser strukturiert und zugänglich gemacht werden.
Linked Open Usable Data (LOUD)
Das Konzept Linked Open Usable Data (LOUD) baut auf Linked Open Data (LOD) auf, geht jedoch einen Schritt weiter, indem es die Nutzbarkeit der Daten in den Vordergrund stellt. LOUD zielt darauf ab, Daten so bereitzustellen, dass sie nicht nur vernetzt und offen sind, sondern auch leicht zugänglich und verständlich für verschiedene Benutzergruppen.
Die fünf Merkmale von LOUD nach Robert Sanderson sind:
1.	Richtige Abstraktion für die Zielgruppe: Daten müssen für verschiedene Zielgruppen zugänglich und verständlich sein.
2.	Niedrige Einstiegsbarrieren: Der Zugang zu den Daten sollte so einfach wie möglich gestaltet sein.
3.	Verständlich durch Introspektion: Daten sollten so strukturiert sein, dass ihre Bedeutung aus der Struktur selbst ersichtlich ist.
4.	Dokumentation: Regeln und Strukturen sollten gut dokumentiert sein, idealerweise mit praktischen Beispielen.
5.	Konsistenz mit minimalen Ausnahmen: Die Datenstruktur sollte konsistent sein und nur wenige Ausnahmen enthalten.
LOUD kombiniert die Vorteile von JSON und Linked Data, indem es strukturierte Daten mit klaren Bedeutungen bietet und Interoperabilität durch gemeinsame Datenmodelle fördert. Ein Beispiel für die praktische Anwendung von LOUD ist lobid-gnd, eine Plattform zur Verwaltung der Gemeinsamen Normdatei (GND).
Metadaten anreichern mit OpenRefine und Wikidata
Ein weiterer spannender Punkt war die Nutzung von OpenRefine zur Anreicherung von Metadaten mit Wikidata. OpenRefine ermöglicht die Datenbereinigung und -anreicherung durch die Integration von externen Datenquellen wie Wikidata.
Der Prozess umfasst:
1.	Import der Beispieldaten: Beispielsweise eine CSV-Datei mit Schriftstellern.
2.	Reconciliation: Abgleich der lokalen Daten mit Wikidata-Daten.
3.	Anreicherung: Hinzufügen von zusätzlichen Informationen aus Wikidata zu den lokalen Daten.
Dieser Prozess erleichtert die Datenverwaltung und verbessert die Datenqualität, indem er zusätzliche Informationen aus zuverlässigen externen Quellen integriert.
Reflexion
Der heutige Tag hat mir viele neue Einblicke in die aktuellen Entwicklungen und Herausforderungen im Bereich der Metadatenverwaltung gegeben. Besonders beeindruckend finde ich die Fortschritte, die mit BIBFRAME und RiC gemacht wurden, um die Bibliotheks- und Archivdaten besser zu vernetzen und zugänglich zu machen. Das Konzept von LOUD hat mir gezeigt, wie wichtig es ist, Daten nicht nur offen, sondern auch nutzbar zu gestalten. Die praktische Anwendung von OpenRefine und Wikidata zur Datenanreicherung verdeutlichte die Möglichkeiten, die moderne Tools bieten, um die Qualität und Konsistenz von Metadaten zu verbessern.
