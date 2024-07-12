# Untersuchung der Integration von KI im TAS

In diesem Ordner werden verschiedene Untersuchungen zur Integration von KI im tutoriellen Assistenzsystem (TAS) von VerDatAs bereitgestellt:

1. Voruntersuchung zur Kontext-Formulierung: Der Vergleich von 8 unterschiedlichen Formaten zur Formulierung des Kontextes, welcher jeweils mit 20 Beispiel-Prompts ausgeführt wurde.
2. Voruntersuchung zur Modell-Analyse: Der Vergleich von 9 unterschiedlichen Sprachmodellen, welcher mit dem zuvor ausgewählten Format zur Kontext-Formulierung sowie mit 20 Beispiel-Prompts ausgeführt wurde.
3. Untersuchung des KI-Einsatzes zur Unterstützung unterschiedlicher Anwendungsszenarien: Der Vergleich von 4 ausgewählten Sprachmodellen, welcher mit dem zuvor definierten Format zur Kontext-Formulierung und 56 Prompts zur Unterstützung verschiedener Anwendungsszenarien ausgeführt wurde.

Jeder Ordner beinhaltet eine Reihe von Unterordnern für die unterschiedlichen Alternativen und hierin jeweils die nachfolgend aufgelisteten Dateien:
* `message_history.json`: Eine Auflistung der Prompts und gegebenen Antworten des Sprachmodells.
* `system_message.txt`: Die verwendete System-Nachricht bei Ausführung dieser Prompts.
