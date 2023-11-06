# Test Driven Development (TDD)

## Was ist TDD?
TDD ist ein Entwicklungs- und Designparadigma für Software, bei dem das Testen von Programmkomponenten dazu verwendet wird, den gesamten Prozess der Softwareentwicklung zu leiten. Das Ziel liegt darin, die Qualität der Software maßgeblich zu erhöhen und den Wartungsaufwand zu verringern. Ursprünglich waren Testen und Entwickeln voneinander entkoppelt. Bei dieser Vorgehensweise können im Schnitt 45 Prozent aller Fehler erkannt bzw. vermieden werden.

## Wie funktioniert TDD?
1. **Schreiben eines Tests:** Test beschreibt, wie sich gewünschte Funktion verhalten soll.
2.	**Test ausführen:** Test schlägt fehl, da es noch keinen Quellcode gibt.
3.	**Implementieren des Codes:** Code entwickeln, der den Test besteht.
4.	**Erneutes Testen:** Code anpassen, bis er Test besteht.
5.	**Refaktorisierung:** Code optimieren, ohne Funktionalität zu beeinträchtigen.
6.	**Wiederholung:** Neue Tests für Anforderungen schreiben.

## Vorteile
- **Frühe Fehlererkennung:** Fehler in sehr früher Entwicklungsphase erkennen, reduziert Kosten für spätere Fehlerbehebungen.
- **Lebendige Dokumentation:** Tests dienen als Dokumentation. Sie beschreiben, wie sich Software verhalten soll, erleichtert Wartbarkeit.
- **Rückverfolgbarkeit:** Tests spiegeln Anforderungen wider. Einfacher sicherstellen, dass Anforderungen umgesetzt wurden.
- **Vermeidung von Over-Engineering:** Code der Test bestehen soll, verhindert unnötige Komplexität.

## Nachteile
- **Anpassung an bestehenden Code:** Existiert bereits Code, kann es schwierig sein, diesen so anzupassen, dass er testbar wird.
- **Zeitaufwand:** Tests zu implementieren kann zunächst mehr Zeit in Anspruch nehmen. Kann in hektischen Projekten hinderlich sein.
- **Lernkurve:** TDD bedarf gewisser Umgewöhnung und Verständnis für die richtige Art und Weise Tests zu schreiben.
- **Zu viele Tests:** TDD kann dazu führen, dass zu viele Tests geschrieben werden. Ändern sich Anforderungen, müssen viele Tests umgeschrieben werden, was mehr Zeit in Anspruch nimmt und die Kosten wieder erhöht.

## Quellen
[wikipedia.org](https://de.wikipedia.org/w/index.php?title=Testgetriebene_Entwicklung&oldid=235708551)
[ryte.com](https://de.ryte.com/wiki/Test_Driven_Development)
[ionos.at](https://www.ionos.at/digitalguide/websites/web-entwicklung/was-ist-test-driven-development/)
[it-agile.de](https://www.it-agile.de/agiles-wissen/agile-entwicklung/was-ist-testgetriebene-entwicklung/)
[freecodecamp.org](https://www.freecodecamp.org/news/learning-to-test-with-python-997ace2d8abe/)

