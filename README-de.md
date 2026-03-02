# Das Damenproblem
[![en](https://img.shields.io/badge/lang-en-green.svg)](https://github.com/danielgafarov/8queens)

Das Ziel des **Damenproblems** ist es, acht Damen so auf einem 8x8 Schachbrett zu platzieren, dass keine zwei Damen einander angreifen. Das bedeutet, dass keine Damen in der gleichen Reihe, Spalte oder Diagonalen stehen dürfen. Insgesamt gibt es **92 Lösungen** für dieses Problem.



---

### Algorithmus Eins: Genetischer Algorithmus
Dieser Ansatz imitiert die Prinzipien der natürlichen Evolution, bei der Organismen ihre Gene an ihre Nachkommen vererben.

* **Zweck:** Dieser Algorithmus dient primär akademischen Demonstrationszwecken. Aufgrund seiner stochastischen Natur ist er für deterministische Probleme in der Praxis oft weniger effizient.
* **Ergebnis:** Er liefert meist nur eine Lösung und garantiert im schlechtesten Fall nicht mal eine der Lösungen zu finden.
* **Performance:** Da Zufallsprozesse (Mutation und Rekombination) eine zentrale Rolle spielen, schwanken die Laufzeiten erheblich.

### Algorithmus Zwei: Backtracking-Suche
Ein Backtracking-Algorithmus erkundet potenzielle Lösungen systematisch in einer baumartigen Struktur.



* **Funktionsweise:** Sobald der Algorithmus erkennt, dass ein Zweig keine gültige Lösung liefern kann (da alle Pfade in diesem Zweig denselben Konflikt aufweisen), verwirft er diesen ("Pruning") und springt zum letzten Entscheidungspunkt zurück.
* **Vorteile:** Dieser Algorithmus findet garantiert **alle** 92 Lösungen und weist eine konsistente, vorhersehbare Laufzeit auf.