
# Skriptum zu WKT2 (SoSe24)

Vorläufiger Entwurf der LaTeX-Mitschrift zu Wahrscheinlichkeitstheorie 2 aus dem Sommersemester 2024. 

Das Skriptum ist noch nicht auf etwaige Fehler (Formatierung, Rechtschreibung, Lücken/Fehler in den Beweisen) korrekturgelesen. 

Fehler, Verbesserungsvorschläge und Ergänzungen bitte ich an 
```corneliush99@univie.ac.at``` zu senden.

### Es fehlt noch:
- Lemma 8.6 inklusive Bemerkungen: *Hier bin ich mir nicht sicher, inwiefern die Aussagen, die wir bereits gezeigt haben, im Kontext des Carathéodory extension theorem verwendet werden.*
- Beweis von Proposition 8.17: *Dieser Beweis hatte (soweit ich mich erinnere) in den Vorlesungen einen Fehler. Die korrekte Version habe ich noch nicht.*
- Beweis von Satz 9.18 (Dominated convergence theorem): *Ich habe den Beweis aus der VO inkl. Anmerkungen aus dem Email vom 19.4.2024, kann die Struktur aber noch nicht ganz nachvollziehen bzw. ausarbeiten.*
- Ich habe leider keine Notizen aus der ersten Vorlesung (8.1, 8.2, 8.3).
- Umlaute und ß müssen noch durch find & replace ergänzt werden.
- Es sind noch einige Kommentare im Code, die noch nicht hier angeführt sind.
### Änderungen
Die größte Änderung war die Änderung der Kapitelnummerierungen und das Weglassen der Abschnittsnummerierungen (da die Sätze nur nach Kepitel nummeriert sind). Da ich diese Änderung erst spät übernommen habe, könnten eventuell Sätze innerhalb des Dokuments falsch zitiert sein (z.B. 11.9 statt 10.9).
- Im ersten Portemanteau theorem (Satz 11.5) habe ich im Beweis gleich am Anfang f_epsilon für alle reellen t statt nur positive definiert. 
- Ich habe einige Formalitäten in Definition 13.1 (bedingter Erwartungswert) ergänzt.
- Ich habe Bemerkung 8.20/21 (Nummerierung aus der VO war nicht eindeutig) gleich an Definition 8.14 angehängt.
- Reihenfolge von 8.15 und 8.16 vertauscht (8.16 folgt nun direkt aus 8.15, was schlüssiger ist).
- Reihenfolge von 8.23 bis 8.25 geändert 
- Dimension d statt k
- In Proposition 9.6 habe ich die Anmerkung, dass die Teilfolgen gegen unendlich gehen müssen weggelassen, da das per Definition einer Teilfolge (mit streng monoton-steigender injektiven Abbildung) sowieso gilt.
- In Satz 9.13 (Continuous mapping theorem) war ich mir nicht sicher ob H zwingend messbar ist. 




### Unklarheiten 
- Im Beweis von Satz 11.10 Teil I habe ich zweimal MONK statt DOMK geschrieben (Ich denke es funktioniert sogar beides, da der Grenzwert der monotonen Folge integrierbar ist).
- Im Beweis von Helly's selection theorem (Satz 11.11) bin ich mir nicht sicher ob n_i ab i=l eine Teilfolge von n_l(1) oder n_l(l) ist.
- In der Aussage von Prokorov's theorem (ii) bin ich mir nicht sicher ob die Konvergenz in Verteilung oder punktweise ist (ich denke in Verteilung, da Helly Konvergenz in Verteilung liefert).
- Mir fehlt eventuell etwas im Beweis von Lévy's continuity theorem (Satz 11.21) bzw. verstehe ich die Schritte im Beweis nicht.
- Im Beweis von Proposition 9.6 Teil I wäre es wahrscheinlich sinnvoll zu erwähnen, warum man die Teil-Teilfolge mit der ersten Eigenschaft so wählen kann. Das ist m.M.n. nicht trivial. 
- Den Beweis von Proposition 9.6 Teil II würde ich gerne noch einmal besprechen.
- Müssen die Funktionen in Satz 9.13 (Continuous mapping theorem) zwingend reellwertig sein?
- Mir sind (8) und (9) in Satz 12.7 (Radon-Nikodym für sigma-endliche Maße) noch nicht ganz klar.
- In Proposition 13.3 (bzw. allgemein in Kapitel 13) haben wir X integrierbar aber erweitert-reell Borel-messbar. Ist X dann auch reell Borel-messbar (da ja X fast sicher endlich ist).
- Warum braucht man in Proposition 13.3 die G-Messbarkeit von E(X)?
- Beispiel 13.2. ist mir noch nicht ganz klar.
- In Proposition 8.10 habe ich angenommen, dass R (statt R*) auch die Produkt-sigma-Algebra erzeugt.
