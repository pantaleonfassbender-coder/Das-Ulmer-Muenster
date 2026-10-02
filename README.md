# Die Bürger bauen. Das Ulmer Münster 1377–1890

Ein Quellenapparat zum Bau des Ulmer Münsters: vom Grundstein 1377 über die Baumeister Ulrich von Ensingen, Matthäus Böblinger und Burkhard Engelberg, die fallenden Steine von 1492 und den Bildersturm von 1531 bis zur Vollendung des Turms 1890. Gemeinfreie Quellen, das lateinische oder frühneuhochdeutsche Original neben einer neuhochdeutschen Arbeitsübersetzung, eine Zeitleiste mit Verweisen in die Texte und eine Liste dessen, was noch kommt.

These, an den Texten zu prüfen: Die Bürger bauten ohne Hilfe und Betteln, wie Felix Fabri 1488 rühmte, und vollenden konnten sie ihren Turm nicht; das tat erst ein anderes Jahrhundert, aus anderen Gründen.

Stufe 1 (in Arbeit) enthält bisher sechs Module:

- **Die Grundsteinlegung, 30. Juni 1377** — Felix Fabri, *Tractatus de civitate Ulmensi* (1488), hg. Veesenmeyer (1889), S. 36–38: Verlegung der Pfarrkirche, Bauplatz, Grundsteinlegung und Fabris Rückblick, Latein mit neuhochdeutscher Arbeitsübersetzung.
- **Der Vertrag des Baumeisters: Ulrich von Ensingen, 1391–1402** — A. W. Fr. Carstanjen, *Ulrich von Ensingen* (1893), Urkundenanhang Nr. I–IX, S. 121–129: der Ulmer Vertrag vom 17. Juni 1392 vollständig (Frühneuhochdeutsch), die Mailänder Einträge 1391–1395 (Latein) und zwei Straßburger Stücke von 1399 und 1402, jeweils mit neuhochdeutscher Arbeitsübersetzung.
- **Die Kirche der Bürger: Patronat und Pfleger** — Felix Fabri, *Tractatus de civitate Ulmensi*, S. 24–27 und 131–132: der Loskauf von den Klöstern Bebenhausen und Reichenau (Bann, 24 000 Gulden, der erste vom Rat präsentierte Pfarrer) und die Pfleger des Rats über Stadt, Pfarrkirche, Spital und Arme, Latein mit neuhochdeutscher Arbeitsübersetzung.
- **Fabris Münster, 1488** — Felix Fabri, *Tractatus de civitate Ulmensi*, S. 39–42 und 140–144: die ‚neun‘ (zehn) Vorzüge der Kirche und die fünf Werke der Stadt, mit dem Plan der Gründer, hinter dem ‚die Kleinmütigen von heute‘ zurückbleiben, Latein mit neuhochdeutscher Arbeitsübersetzung.
- **Die Ordnung der Steinmetzen, Regensburg 1459** — C. A. Heideloff, *Die Bauhütte des Mittelalters in Deutschland* (1844), Beilage Nro. 1, S. 34–42: fünfzehn Artikel der Hüttenordnung nach der Straßburger Fassung, Frühneuhochdeutsch (Fraktur am Seitenbild gelesen) mit neuhochdeutscher Arbeitsübersetzung.
- **1492: die fallenden Steine** — Elias Frick, *Templum Parochiale Ulmensium* (1718), S. 45–47, und Rudolf Pfleiderer, *Münsterbuch* (1907), S. 12–13: Steinfall, Böblingers Weggang, der Brief an Esslingen 1493 und Engelbergs Unterfangung 1494–1502, in zwei späteren Stimmen (Fraktur am Seitenbild gelesen); für 1492 liegt keine zeitgenössische Quelle im Volltext vor.

Tafeln: Ulm in Schedels Weltchronik (1493); Ulrichs Meisterzeichen nach Carstanjen (1893); der Münsterplatz nach Merian (1643); der Planriss des Westturms (Ende 15. Jh.); Falgers Westansicht (1829); Roriczers Fialen nach Heideloff (1844); Böblingers Ölberg nach Pfleiderer (1907). Zehn Vergleiche: Was ein Meister kostet (Ulm und Mailand), Darf der Meister anderswo bauen? (Ulm und Straßburg), Ohne Betteln (Grundstein und Armenpfleger), Wer ist der Bauherr? (Vertrag 1392 und Pfleger), Lob und Klage (Fabri über Gründer und Heutige), Zweimal der Loskauf (Fabris zwei Berichte), Der Plan bindet (Ordnung 1459 und Fabri), Wie viele Lehrlinge? (Vertrag 1392 und Ordnung 1459), Floh der Meister? (Frick und Pfleiderer), Wie der Rat seine Meister band (Verträge 1392 und 1480).

Geplante Module in der Reihenfolge der Arbeit: siehe `data/modules.json`.

## Daten bauen

```
python tools/build-grundstein.py
python tools/build-ensinger.py
python tools/build-buergerkirche.py
python tools/build-fabri1488.py
python tools/build-huette.py
python tools/build-turm1492.py
python tools/verify.py
```

Das Begleitspiel *Ohne Hilfe und Betteln* nimmt seinen Titel von Fabri.

Code MIT; Editionen und Arbeitsübersetzungen CC0; redaktionelle Texte CC BY 4.0 (siehe `LICENSES.md`).
