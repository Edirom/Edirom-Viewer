Edirom-Viewer
=============

A Java-based software that brings paperbased historic-critical editions of musicians handwritings to the pc.

## Edirom Viewer 1.1.31 (2012-01-19)

* Version 1.6.1 von MusicalSymbolsTextGrid eingebaut
* Fehler bei der Anzeige von Anmerkungsdetails im Suchfenster behoben
* Auslesen von Objekten im Suchfenster nun nach @sortNo sortiert

## Edirom Viewer 1.1.30 (2012-01-05)

* Version 1.6 von MusicalSymbolsTextGrid eingebaut
* Temporäres Verzeichnis für schreibgeschützte Umgebungen umgestellt (altes Vorgehen verhinderte zwei parallel ausgeführte Edirom-Instanzen)
* Attributangaben in verschachtelten Links in Texten werden nun korrekt ausgelesen
* Datumsangaben in Quellen- oder Textmetadaten werden nun sowohl aus einem @when-Attribut und aus dem Inhalt ausgelesen

## Edirom Viewer 1.1.29 (2011-11-15)

* Alternativtexte für musikalische Sonderzeichen in Anmerkungstooltips nun auch mit Schriftart "MusicalSymbolsTextGrid" möglich

## Edirom Viewer 1.1.28 (2011-09-14)

* Falscher Aufbau der Zip-Archive im Edirom Updater unter Windows behoben

## Edirom Viewer 1.1.27 (2011-06-28)

* Tooltips der Anmerkungen in Texten sind nun identisch mit denen in den Notentexten
* Geschwindigkeit beim Laden von Texten mit Anmerkungen drastisch erhöht
* Beim Öffnen von Textfenstern aus dem Konkordanz-Navigator heraus werden nun Elemente im Text korrekt angesprungen
* Wenn in einem Textfenster die Anmerkungen angezeigt werden und der Text über einen Link ausgetauscht wird, werden in dem neuen Text ebenfalls die Anmerkungen angezeigt, falls denn welche da sind

## Edirom Viewer 1.1.26 (2011-06-16)

* Englische Hilfe integriert, deutsche überarbeitet
* Angaben der Quellen in den Tooltips der Anmerkungen wieder aufgenommen
* Prioritäten werden nun analog zur Darstellung im Quellenfenster auch im Suchfenster nur dann angezeigt, wenn im gesamten Werk mehr als nur eine Priorität genutzt wurde
* Tooltip für Kategorien in der Toolbar der Quellenfenster nun mit Prefix möglich
* Dokumente werden nun bei multiplen Links im Dokument (Umgestaltung über IDs und CSS-Klassen) nicht mehrfach neu geladen
* Umgestaltung über CSS-Klassen nun auch bei mehrfachen Klassen in einem Element möglich
* Spezielle XML-Zeichen und Maskierungen werden bei Namen und Titeln nun korrekt ausgelesen
* Bugfixes

## Edirom Viewer 1.1.25 (2011-04-26)

* Neues Programm-Icon für den Edirom Updater

## Edirom Viewer 1.1.24 (2011-02-27)

* Edirom-Link für das Setzen von Einstellungen: `edirom://setPreferences[]` (Beispiel: `edirom://setPreferences[class_de.edirom.Edirom__user.language=de,edition-12345678__language=de]`)
* Anmerkungsfenstertitel mit beliebigem Trennzeichen (Sprachdateieintrag: `Annotation_window_colon`) (default: `Annotation_window_colon=: `)
* Label für Participants im Anmerkungsfenster (Plural/Singular) korrigiert
* Anzeige von Participants im Anmerkungsfenster so umgestellt, dass mehrfache Vorkommen z.B. einer Quelle nur einmal angezeigt werden
* Es können über den Eintrag `annotation_window_hide_sources_texts` Notentexte und Texte aus den Metadaten der Anmerkungen herausgehalten werden (default: `annotation_window_hide_sources_texts=none;` Beispiel: `annotation_window_hide_sources_texts=source12,text-1`)
* CSS-Klassen für Participants in den Metadaten der Anmerkungen eingeführt (`participant, participant_first, participant_last`). Falls nur ein participant da ist, bekommt er sämtliche Einträge.
* Fehler beim Auslesen sprachspezifischer Daten behoben.
* Fehler beim Anzeigen von FacsimileFlowItems gefixt

