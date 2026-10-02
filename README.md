# Die Bürger bauen. Das Ulmer Münster 1377–1890

Ein Quellenapparat zum Bau des Ulmer Münsters: vom Grundstein 1377 über die Baumeister Ulrich von Ensingen, Matthäus Böblinger und Burkhard Engelberg, die fallenden Steine von 1492 und den Bildersturm von 1531 bis zur Vollendung des Turms 1890. Gemeinfreie Quellen, das lateinische oder frühneuhochdeutsche Original neben einer neuhochdeutschen Arbeitsübersetzung, eine Zeitleiste mit Verweisen in die Texte und eine Liste dessen, was noch kommt.

These, an den Texten zu prüfen: Die Bürger bauten ohne Hilfe und Betteln, wie Felix Fabri 1488 rühmte, und vollenden konnten sie ihren Turm nicht; das tat erst ein anderes Jahrhundert, aus anderen Gründen.

Stufe 1 (in Arbeit) enthält bisher zwei Module:

- **Die Grundsteinlegung, 30. Juni 1377** — Felix Fabri, *Tractatus de civitate Ulmensi* (1488), hg. Veesenmeyer (1889), S. 36–38: Verlegung der Pfarrkirche, Bauplatz, Grundsteinlegung und Fabris Rückblick, Latein mit neuhochdeutscher Arbeitsübersetzung.
- **Der Vertrag des Baumeisters: Ulrich von Ensingen, 1391–1402** — A. W. Fr. Carstanjen, *Ulrich von Ensingen* (1893), Urkundenanhang Nr. I–IX, S. 121–129: der Ulmer Vertrag vom 17. Juni 1392 vollständig (Frühneuhochdeutsch), die Mailänder Einträge 1391–1395 (Latein) und zwei Straßburger Stücke von 1399 und 1402, jeweils mit neuhochdeutscher Arbeitsübersetzung.

Tafeln: Ulm in Schedels Weltchronik (1493); Ulrichs Meisterzeichen nach Carstanjen (1893). Zwei Vergleiche: Was ein Meister kostet (Ulm und Mailand), Darf der Meister anderswo bauen? (Ulm und Straßburg).

Geplante Module in der Reihenfolge der Arbeit: siehe `data/modules.json`.

## Daten bauen

```
python tools/build-grundstein.py
python tools/build-ensinger.py
python tools/verify.py
```

Das Begleitspiel *Ohne Hilfe und Betteln* nimmt seinen Titel von Fabri.

Code MIT; Editionen und Arbeitsübersetzungen CC0; redaktionelle Texte CC BY 4.0 (siehe `LICENSES.md`).
