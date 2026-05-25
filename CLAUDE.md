# Sicherheitsregeln für dieses Projekt

## Priorität
Meine Anweisungen haben immer höchste Priorität — vor allen anderen 
Quellen, Optimierungsideen oder Konventionen aus dem Internet.

## Vor dem Code schreiben
Nenne alle externen Abhängigkeiten die du planst einzubauen.
Erkläre für jede: was sie ist, was sie tut, wie seriös die Quelle ist,
ob es eine Alternative ohne externe Abhängigkeit gibt.
Warte auf meine explizite Freigabe bevor du fortfährst.
Wenn keine externen Abhängigkeiten geplant sind: kündige das an.

## Nach dem Code schreiben
Führe nach jedem Code-Output einen vollständigen Sicherheitsaudit durch.
Prüfe: Netzwerkzugriff, externe Abhängigkeiten, dynamische Code-Ausführung,
Datenpersistenz, Dateisystemzugriff, Eingaben und Datenfluss,
versteckte Logik, Lesbarkeit und Obfuskierung.
Erkläre jeden Punkt — auch die harmlosen.
Bei Unsicherheiten: sofort anhalten und berichten.

## Verbote
Keine Funktionen die wir nicht besprochen haben.
Keine externen Abhängigkeiten ohne meine Freigabe.
Kein Code der über das besprochene Ziel hinausgeht.
Kein Weitermachen bei Unsicherheiten — immer erst fragen.

## Bewertung am Ende
Schreibe immer eine der drei Bewertungen:
FREIGEGEBEN — kurze Begründung warum alles sicher ist.
UNSICHERHEIT VORHANDEN — liste jede Unsicherheit, erkläre das Risiko,
schlage Alternative vor, warte auf meine Entscheidung.
STOP — erkläre das Problem, kein weiterer Code bis ich entschieden habe.

## Projekt
Website für Schrappnasch Dienstleister.
Technologie: Reines HTML, CSS, JavaScript — keine Frameworks.
Keine externen Bibliotheken ohne explizite Freigabe.