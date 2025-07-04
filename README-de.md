# Damenproblem
[![en](https://img.shields.io/badge/lang-en-green.svg)](https://github.com/danielgafarov/8queens/blob/main/README.md)

Das Ziel des Damenproblems ist es acht Damen auf einem 8x8 Schachbrett zu platzieren, so dass keine Damen sich gegenseitig angreifen. Das bedeutet, dass keine Damen in der gleichen Reihe, Spalte or Diagonalen sein dürfen. Es gibt ingesamt 92 Lösungen für dieses Problem.
### Algroithmus Eins: Genetischer Algorithmus
Dieses Herangehensweise immitiert die Natur und wie Organismen ihre Gene an ihre Nachkommen vererben. Dieser Algorithmus hat einen akademischen Zweck und eignet sich nicht für das Lösen von Problemen in der Wirtschaft. Er liefert nur eine Lösung und im schlimmsten Fall sogar gar keine. Da in genetischen Prozessen der Zufall eine Rolle spielt, unterscheiden sich die Laufzeiten für den Algorithmus deutlich.
### Algorithmus Zwei: Backtacking Search
Ein Backtracking Algorithmus erstellt potentielle Lösungen in einer Baum ähnlichen Struktur. Sobald der Algorithmus erkennt, dass ein Zweig keine Lösungen liefern kann, da alle potentiellen Lösungen in diesem Zweig das gleiche Problem haben, verwirft es diesen Zweig und sucht in einem anderen Zweig weiter nach Lösungen. Dieser Algorithmus findet alle Lösungen und bracuht immer die selbe Zeit.
