# Polymorphie
## Modul2

### 1. Vortrag Vererbung

- Superklassen geben Subklassen alle Methoden und Datenfelder mit
- Desto weiter unten Klassen in einem Vererbungsbaum sind, desto spezifischer wird die implementierung, was das Beispiel in diesem Vortag gut zeigt
- Durch Vererbung kann man sehr gut Code duplizierung vermeiden
- Vererbung bietet zudem eine einfachere Erweitbarkeit.
- Vererbung ist eine Einbahnstraße, die Superklasseweiß nichts über die Datenfelder ihrer Subklasse.

### 2. Vortag Polymorphie

- Der deklarierte Typ einer Variable ist ihr statischer Typ.
- Der Typ des Objekt, auf das eine Variable verweist, ist ihr dynamischer Typ.
- Beim Überschreiben wird die Subklassenmethode aufgerufen, die Version der Superklasse wird überschrieben.
- Eine polymorphe Variable kann Objekte verschiedener Typen speichern.
- Bei einem Polymorphenmethodenaufruf hängt die version der Methode von dem dynamischen Typ ab.

### 3. Vortrag Zentrale Konzepte

Konstitutive Teilkonzepte des Methodenpolymorphismus

- Vererbung
- Überschreiben von Methoden
- Ersetzbarkeit
- Dynamische Bindung

### 4. Vortrag Vorgangsweise für Polymorphe Codestrukturen

Wie soll man vorgehen, beim Aufbau einer Polymorphen Codebasis?

- Vererbung einsetzen
- Vollständige Schnittstelle bereistellen in den oberen Klassen
- Überschreiben von Methoden mit subtypenabhängiger Funktionalität
- Entkopplung bzw. Ersetzbarkeit anweden (bei der Verwendung der polymorphen Klassenhierarchie)
- dynamische Bindung nutzen (eingentlicher polymorpher Methodenaufruf)