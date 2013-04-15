WBA2SS13_Phase2
===============

Idee für Phase 2:

Verteiltes Quiz Über einen Client werden die Fragen bei allen Teilnehmer gleichzeitig angegeben, diese werden duch Publish Subscribe verteilt. Anmeldung zum Quiz sowie die Beantwortung der Fragen erfolgen durch REST.
//Die Frage sind entweder vorgefertigt auf einem Server.Nutzer können selbst ein Quiz erstellen und hochladen.
//Die Punkteverteilung ist nach Antworgeschwindigkeit gestaffelt.
//Nutzer können selbst Fragen(samt Antworten), in den Fragenpool stellen, nachdem sie von einem moderator überprüft wurden.
//Veto Recht, wenn niemand eine Antwort weiß, wird die Frage aus dem aktuellen Quiz genommen und ggf. der Schwierigkeitsgrad der Frage bearbeitet.

//Joker werden mit gesammelten Punkten bezahlt Joker: 50/50, Hint, richtige Lösung, lokale, Quizbezogene Punkte werden in globale Punkte umgerechnet.
// Im "Warteraum" haben die wartenden User die Möglichkeit zu chatten. //Nutzer können andere Nutzer zu einem Quiz einladen.

Informationen die übertragen werden müssen: //Informationen zu einem einzelen Quiz: Schwierigkeitsgrad, ggf. autor, Anzahl der Fragen, (anzahl der Wartenden Teilnehmer, min 5), Bewertung, Themengebiet
//Informationen über Nutzer: Bentzernamen, Mitglied seit, beantwortete Fragen, letztes gespieltes Quiz
// Informationsänderung bei Fragen: Zeit, Antworten der Mitspieler, gewonnene Punkte, benutzte Joker
