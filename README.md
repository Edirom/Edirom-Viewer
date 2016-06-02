Edirom-Viewer
=============

A Java-based software that brings paperbased historic-critical editions of musicians handwritings to the pc.

## Edirom Viewer 1.1.24 (2011-02-27)

* Edirom-Link für das Setzen von Einstellungen: `edirom://setPreferences[]` (Beispiel: `edirom://setPreferences[class_de.edirom.Edirom__user.language=de,edition-12345678__language=de]`)
* Anmerkungsfenstertitel mit beliebigem Trennzeichen (Sprachdateieintrag: `Annotation_window_colon`) (default: `Annotation_window_colon=: `)
* Label für Participants im Anmerkungsfenster (Plural/Singular) korrigiert
* Anzeige von Participants im Anmerkungsfenster so umgestellt, dass mehrfache Vorkommen z.B. einer Quelle nur einmal angezeigt werden
* Es können über den Eintrag `annotation_window_hide_sources_texts` Notentexte und Texte aus den Metadaten der Anmerkungen herausgehalten werden (default: `annotation_window_hide_sources_texts=none;` Beispiel: `annotation_window_hide_sources_texts=source12,text-1`)
* CSS-Klassen für Participants in den Metadaten der Anmerkungen eingeführt (`participant, participant_first, participant_last`). Falls nur ein participant da ist, bekommt er sämtliche Einträge.
* Fehler beim Auslesen sprachspezifischer Daten behoben.
* Fehler beim Anzeigen von FacsimileFlowItems gefixt

