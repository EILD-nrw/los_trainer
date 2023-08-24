# LOS-Trainer

## Beschreibung
Mit dem LOS-Trainer (LOS = Logisch Objektrelationales Schema) wird, ausgehend von einer Phrase, die Überführung einer Beziehung zwischen zwei Entitäten eines ER-Diagramms in ein logisches objektrelationales Schema trainiert. Es gilt die nötigen Tabellen oder Typen anzulegen, die erforderlichen Objektidentifikatoren, Referenzen oder Einbettungen zu ergänzen und die Richtung festzulegen, in der die Objekte miteinander in Beziehung stehen.

## Systemanforderungen
Voraussetzung für die App ist ein gängiger Webbrowser (z.B. Firefox, Google Chrome, Microsoft Edge oder Safari) mit aktiviertem JavaScript in einer aktuellen Version.

## Installation
Die Webanwendung kann über GitHub Pages in ihrer Basiskonfiguration ohne Installation über die folgende Web-URL direkt genutzt werden: https://eild-nrw.github.io/los_trainer/.
Über die Web-URL ist die Webanwendung immer auf dem neusten Stand und muss nicht von Hand aktualisiert werden.

Alternativ kann das Repository als ZIP-Datei heruntergeladen, auf einem beliebigen Webspace entpackt und durch den Aufruf der enthaltenen `index.html` gestartet werden.
Die ZIP-Variante hat den Vorteil einer von GitHub unabhängigen Version ohne externe Abhängigkeiten mit weitreichender individueller Anpassbarkeit.

Eine dritte Möglichkeit ist ein _Fork_ des Repository, der anschließend über GitHub Pages veröffentlicht wird.
Diese Variante hat den Vorteil, dass kein eigener Webspace benötigt wird und gleichzeitig auch die individuelle Anpassbarkeit gegeben ist.

In einer Lernplattform (z.B. ILIAS oder Moodle) kann die App entweder über die Web-URL oder über das Hochladen der ZIP-Datei integriert werden.

## Anpassbarkeit

Durch das Editieren der im Repository enthaltenen `resources/resources.js` können weitreichende individuelle Anpassungen vorgenommen werden.
Layout und Design können über die `resources/styles.css` angepasst werden.
Die `resources/templates.js` enthält die HTML-Templates, in der bei Bedarf weitere HTML-ID's und HTML-Klassen ergänzt werden können, um das Selektieren von HTML-Elementen im CSS zu erleichtern.
Wer über die nötigen Programmierkenntnisse verfügt, kann auch die Logik des interaktiven Trainers in der `ccm.los_trainer.js` anpassen.
Es handelt sich dabei um eine auf der _ccmjs_-Webtechnologie basierende Webkomponente.

## Datenverarbeitung
In der unveränderten Basiskonfiguration werden an keiner Stelle Benutzer-spezifische Daten verarbeitet.
Es handelt sich um reine Selbsttests mit direktem Feedback, was richtig/falsch beantwortet wurde.
Es existieren keine Abhängigkeiten zu externen Servern und es findet entsprechend kein Datenaustausch mit anderen Servern statt.

## Hintergrundinformationen
Der [LOS-Trainer](https://github.com/eild-nrw/los_trainer) wurde ausgehend
vom [ER-REL-Trainer](https://github.com/eild-nrw/los_trainer)
von Jan Hase als Bachelorarbeit im Rahmen
des [EILD-Projekts](https://eild.nrw) an
der [Hochschule Bonn-Rhein-Sieg](https://h-brs.de) entwickelt.
Dieses Repository enthält Software unter [MIT-Lizenz](/LICENSE) und Content
unter [CC0-Lizenz](https://creativecommons.org/publicdomain/zero/1.0/deed.de).
Content sind insbesondere die Phrasen in der Basiskonfiguration, ausgenommen sind die verwendeten Logos.

## Kontakt
Wir freuen uns über jedes Feedback und beantworten gern Ihre Fragen.
Hierfür können Sie sich jederzeit (auch nach dem Ende des EILD-Projekts) an den Entwickler André Kless wenden.

Email: andre.kless@h-brs.de | Web: https://www.h-brs.de/de/inf/andre-kless

![Logos von Projekt, Kooperationspartner und Förderer](/resources/img/logos.jpg)
