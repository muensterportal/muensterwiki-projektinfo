# Münsterwiki Projektinfo
Allgemeine Informationen zum Münsterwiki Projekt

## Wiki-Struktur
* Der Eingangspunkt ist eine Startseite, die auf die ***Themen-Landingpages*** weiterverzweigt: 
  * Integrative Themen (KIM)
    * Arbeit, Aufenthalt, Wohnen, Gesundheit, Bildung
  * Freizeitthemen
    * Hofläden, Happy Hours, Termine
  * Stadtteilthemen
    * TBD
  * "Altes Münsterwiki" = bestehende Inhalte
    * Wie präsentieren wir die bestehenden Inhalte am besten?

Konkrete TODOs für 28.11.
* [ ] Übersetzungsfunktion einbauen
* [ ] Struktur für KIM Landingpage erstellen 
* [ ] Themenübersichtsseiten müssen visuell ansprechend sein 

Offene Fragen
* Wie soll die Seite eigentich heißen? ***MünsterWiki***?
* Struktur des Wiki: Kategorien, Tags .. etc. Was für Möglichkeiten gibt es? Was sollten wir nutzen?
* Inhaltlich komplett getrennte Themen, wie können wir die unterbringen?
* Gibt es einen WISIWYG-Editor für die Mediawiki Inhalte? Der Textedtior ist nicht niederschwellig genug
* Wie kann man auf den Inhalte-Seiten Bilder einbauen  
* Wie kann man eine Liste von Objekten mit Bildern machen? z.B. für die Liste von Hofläden, Liste von Happy Hours, ..
* Gibt es eine Logdatei darüber, was mit der Wiki-Suchfunktionen gesucht wurde?
* Suchfunktion - Was machen wir mit der Perplexity Suche?

Zu klärende administrive Punkte
* Hosting
* Übersetzung
  * Wir wollen nur auf deutsch pflegen.
  * Wir brauchen einen Sprachen-Auswahl-Button, der die Seite automatisch in die entsprechende Sprache übersetzt, welche Möglichkeiten haben wir?
    * Link zu einem externem Übersetzungsservice per Javascript (=> ggf. kostenfplichtig)
    * In Browser eingebaute Übersetzungsfunktionen
    * Plugin für MediaWiki (=> scheint es nicht zu geben, weil die Policy von Mediawiki ist, dass die übersetzten Seiten einzeln gepflegt werden)
    * Selbst einen Übersetzungsdienst hosten (=> gibt's das? kompliziert..)
    * Idee: Schauen, wie machen es andere
      * www.stadt-koeln.de www.duesseldorf.de -> Nutzen conword.io, Preise nur auf Anfrage
* Barrierefreiheit
  * Komponenten
    * Einfache Sprache
    * Vorlesefunktion
    * Blindenkompatibilität
  * Barrierefreiheitssstärkungsgesetz checken, ob wir darunter fallen und was wir verpflichtend machen müssen.
  * Wie machen es die anderen? "Eye-Able" scheint bei anderen Kommunen verbreitet -> kostet das was?
  * Gute Seite dazu: https://www.barrierefreiheit.online/beitraege/overlays-fuer-barrierefreiheit
  * Fazit: Diese Tools taugen nichts, man muss statt dessen "nur" seine Webseite vernünftig mit den Standard-HTML Auszeichnungsattributen versehen. Zitat: "Die Anforderung der digitalen Barrierefreiheit ist deshalb logisch und sinnvoll: Websites sollen auf assistive Technologien richtig reagieren. Der Ansatz der Overlay-Tools steht dem entgegen: Hier sollen die Nutzer agieren. Kleine Analogie zur Offline-Welt: Das wäre in etwa so, als müssten Sie vor dem Betreten eines Geschäfts am Eingang Ihre eigene Brille abgeben eine andere, die der Laden bereitstellt, auswählen und probieren. Danach dürfen Sie dann shoppen."

Welche Kosten entstehen
* Feste laufende Kosten
  * Hosting
  * Übersetzungsfunktion
  * KI-Suchfunktion(?)
  * Barrierefreiheitsmodul(?)
  * Arbeitszeit der Mitarbeitenden
    * Redaktion (Moderation, Endredaktion)
    * Technik-Administration (Servermanagement, Updates, Wartung, Notfall)
    * Öffentlichkeitsarbeit & Community-Management(?)
* Optional 
  * Wikitreffen & Community-Events veranstalten
  * Werbung
